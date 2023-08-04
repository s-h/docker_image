ARG VERSION=v3.16
FROM docker.io/alpine:latest
RUN echo "https://mirrors.aliyun.com/alpine/v3.16/main/" > /etc/apk/repositories
RUN echo "https://mirrors.aliyun.com/alpine/v3.16/community/" >> /etc/apk/repositories
RUN ["apk","update"]
RUN ["apk","add","curl"]