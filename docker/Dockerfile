FROM ubuntu
RUN apt update -y
RUN apt install apache2 -y
COPY /home/ec2-user/index.html /var/www/html/
CMD ["/usr/sbin/apachectl", "-D" , "FOREGROUND"]
