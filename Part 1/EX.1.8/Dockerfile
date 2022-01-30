FROM ubuntu:18.04

COPY curler.sh .

RUN apt-get update

RUN apt-get -y install sudo

RUN sudo apt -y install curl

CMD ./curler.sh