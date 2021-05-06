FROM ubuntu:18.04

RUN apt-get update
RUN apt-get install nginx -y
RUN apt-get install supervisor -y
RUN echo 'hello world 4.0' > /var/www/html/index.html

CMD nginx -g 'daemon off;'
