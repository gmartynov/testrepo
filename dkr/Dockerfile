FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd tree
RUN apk --purge -v del by netcat-openbsd
CMD tail -f /dev/null
