FROM debian:jessie

RUN mkdir -p /opt/os

WORKDIR /opt/os

RUN apt-get update -y && apt-get install build-essential gdb nasm qemu  vim -y

RUN groupadd -g 999 llp && useradd -r -u 999 -g llp llp

USER llp
