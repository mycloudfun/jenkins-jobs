FROM alpine:latest

ADD pause /bin/

RUN apk add --update git curl bash \
  && rm -rf /var/cache/apk/*
