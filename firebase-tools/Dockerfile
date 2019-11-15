FROM openjdk:latest

RUN yum update -y \
  && yum install -y curl \
  && curl -sL https://rpm.nodesource.com/setup_10.x | bash - \
  && yum install -y nodejs \
  && npm i -g firebase-tools@7.6.1 \
