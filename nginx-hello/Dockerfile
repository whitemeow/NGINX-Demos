FROM nginx:mainline-alpine
RUN rm /etc/nginx/conf.d/*
ADD hello.conf /etc/nginx/conf.d/

RUN set -x && \
    echo "Hello, tea" > /usr/share/nginx/html/index.html
