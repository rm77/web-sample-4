FROM php:7.4-fpm-alpine3.10

RUN apk update && apk add mysql-client && docker-php-ext-install pdo pdo_mysql && docker-php-ext-enable pdo_mysql
