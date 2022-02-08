ARG VERSION=20.04 

FROM ubuntu:${VERSION}
ENV DEBIAN_FRONTEND=nonintercative
RUN apt-get update && apt-get install -y \
    build-essential \
    clang \
    cmake 
WORKDIR /build