FROM php:fpm-alpine  
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
CMD ["php-fpm"]
EXPOSE 9000
