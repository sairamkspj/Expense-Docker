FROM nginx
RUN rm -rf /usr/share/nginx/html
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/conf.d
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
