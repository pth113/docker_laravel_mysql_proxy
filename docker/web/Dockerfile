FROM nginx:1.10-alpine
#RUN addgroup -g 1001 www
#RUN adduser -S www -u 1001 -G www
ADD docker/web/vhost.conf /etc/nginx/conf.d/default.conf
COPY docker/web/nginx.conf /etc/nginx/nginx.conf
COPY public /var/www/public