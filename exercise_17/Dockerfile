FROM ubuntu:20.04

WORKDIR /usr/src/app

COPY website.sh .

RUN apt-get -y update && apt-get -y upgrade

RUN apt-get -y install curl

CMD ./website.sh
