FROM ubuntu:22.04

WORKDIR /usr/src/app


COPY script.sh .


RUN apt update && apt upgrade -y && apt install -y curl


CMD ./script.sh
