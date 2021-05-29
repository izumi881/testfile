FROM webdevops/php-nginx:7.4

RUN ["/bin/rm","/opt/docker/etc/nginx/vhost.common.d/10-php.conf"]
COPY --from=composer /usr/bin/composer /usr/bin/composer