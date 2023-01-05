FROM ghcr.io/vektor-docker/docker-nginx-base:3.0
MAINTAINER Viktor Verbitsky <vektory79@gmail.com>

ENV USE_DHPARAM="no"

COPY src/main/docker /

RUN chmod --recursive +x /etc/my_init.d/*.sh /etc/service /usr/local/bin
