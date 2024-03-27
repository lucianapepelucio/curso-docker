ARG TAG=latest

FROM alpine:$TAG
#FROM alpine:3.16.2

ARG CONTAINER_NAME_ARG
#ARG CONTAINER_NAME_ARG=Container-A

ENV CONTAINER_NAME_ENV=${CONTAINER_NAME_ARG:-"Container A"}
#ENV CONTAINER_NAME_ENV=${CONTAINER_NAME_ARG:-Container-A}

LABEL maintainer="Luciana Pepe<luciana.lucio@g.globo>"