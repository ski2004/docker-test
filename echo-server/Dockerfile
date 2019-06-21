FROM node:11.6
MAINTAINER ski2004

#RUN apk update && apk upgrade
RUN \
mkdir /opt/laravel-echo-server && \
cd /opt/laravel-echo-server && \
npm install -g laravel-echo-server 


EXPOSE 6002

WORKDIR /opt/laravel-echo-server
CMD ["laravel-echo-server", "start"]
