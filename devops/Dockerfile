FROM alpine
RUN apk update && apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py3-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null