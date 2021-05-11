FROM alpine:3.7

RUN apk --no-cache upgrade && apk --no-cache add samba samba-common-tools

EXPOSE 445/tcp

ENTRYPOINT ["smbd", "--foreground", "--log-stdout"]
