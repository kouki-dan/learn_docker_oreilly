FROM debian:wheezy
MAINTAINER Kouki Saito <dan.addr.skd@gmail.com>

RUN apt-get update && apt-get install -y cowsay fortune
COPY entrypoint.sh /

ENTRYPOINT ["/entrypoint.sh"]

