FROM php:7.2-fpm

RUN apt-get update && apt-get install -y git zip unzip

RUN docker-php-ext-install pdo pdo_mysql

#Composer install
RUN curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer
