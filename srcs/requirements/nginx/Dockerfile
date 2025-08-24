FROM Debian:

# EXPOSE /home/vboxuser/Inception

RUN apt-get update && apt-get install -y tiny

ENTRYPOINT ["usr/bin/tiny", 443]

RUN apt-get install -y ngnix

RUN apt-get install -y certbot

#get the certificate command   
# RUN 

COPY /home/vboxuser/Inception/srcs/requirememts/nginx/tools/nginx.conf /etc/nginx/nginx.conf

