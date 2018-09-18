FROM ubuntu:14.04

LABEL maintainer="vmukashi7@gmail.com"

RUN apt-get update &&											\
	apt-get install -y sudo	&&									\
	apt-get install -y git &&									\
    apt-get install -y curl openssh-server ca-certificates &&	\
	apt-get install -y postfix
	
RUN curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ee/script.deb.sh | sudo bash

#RUN sudo EXTERNAL_URL="http://gitlab.example.com" apt-get install -y gitlab-ee
