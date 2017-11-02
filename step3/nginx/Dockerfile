FROM nginx:1.13.6-alpine

RUN rm -f /etc/nginx/conf.d/default.conf
COPY ./conf.d/ /etc/nginx/conf.d
COPY ./nginx.conf /etc/nginx/nginx.conf
