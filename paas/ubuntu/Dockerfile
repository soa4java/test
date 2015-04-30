#test

FROM ubuntu:latest
MAINTAINER ghg <soa4java@163.com>
RUN apt-get update && apt-get install -y redis-server
EXPOSE   6379
ENTRYPOINT  ["/usr/bin/redis-server"]
