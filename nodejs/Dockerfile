FROM khulnasoft/ubuntu
MAINTAINER Khulnasoft DevOps <info@khulnasoft.com>

RUN \
  add-apt-repository -y ppa:chris-lea/node.js && \
  apt-get update && \
  apt-get -y install \
          nodejs && \
  rm -rf /var/lib/apt/lists/*
