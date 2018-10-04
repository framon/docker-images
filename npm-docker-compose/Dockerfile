FROM node:8-jessie
MAINTAINER Fábio Ramon <framon@monzeu.eti.br>

RUN apt-get update && apt-get install -y python-pip python-dev && \
 pip install docker-compose && \
 rm -rf /var/lib/apt/lists/*

CMD bash
