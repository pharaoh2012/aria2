FROM gliderlabs/alpine:3.3

RUN apk-install nginx

COPY nginx.conf /usr/local/nginx/

VOLUME /home/aria2

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
