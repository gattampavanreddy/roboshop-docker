FROM nginx:1.24.0
# remove the default content of nginx 
RUN rm -f /usr/share/nginx/html/index.html
RUN rm -f /etc/nginx/nginx.conf
RUN rm -f /etc/nginx/conf.d/default.conf
# placed our own nginx.conf and static content
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/