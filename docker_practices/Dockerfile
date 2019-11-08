FROM ubuntu:18.04

LABEL MAINTAINER=javy
LABEL DEPARTMENT=Desarrrollo
LABEL VERSION=2.5.7

RUN apt-get update
RUN apt-get install nginx -y

RUN echo '<marquee>hola caracola</marquee>' \
        > /var/www/html/index.html

EXPOSE 80

CMD ["nginx2","-g","daemon off;"]