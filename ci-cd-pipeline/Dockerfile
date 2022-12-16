FROM nginx:alpine
RUN chmod g+rwx /var/cache/nginx/ /var/run /var/log/nginx
COPY app/html/index.html /var/www/
COPY app/nginx.conf /etc/nginx/nginx.conf
EXPOSE 8000
