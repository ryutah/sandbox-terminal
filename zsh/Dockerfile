FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update -y \
 && apt-get install -y software-properties-common

RUN add-apt-repository -y \
      ppa:spvkgn/exa

RUN apt-get update -y \
 && apt-get install -y \
      zsh \
      git \
      vim \
      curl \
      exa
