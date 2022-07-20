FROM alpine:latest

RUN apk -U upgrade && apk add --no-cache \
    nginx \
    php8-fpm

EXPOSE 8080

CMD nginx ; php-fpm8
