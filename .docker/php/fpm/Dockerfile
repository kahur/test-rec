FROM php:8.3-fpm

RUN apt-get update -y
RUN apt-get install curl

RUN docker-php-ext-install pdo pdo_mysql

WORKDIR /code
