FROM mysql:5.7.19

MAINTAINER Fabiano Santos <fabiodeveloperti@gmail.com>

RUN sed -i -e"s/^bind-address\s*=\s*127.0.0.1/bind-address = 0.0.0.0/" /etc/mysql/my.cnf

CMD ["mysqld"]

EXPOSE 3306
