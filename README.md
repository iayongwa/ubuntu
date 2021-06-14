Ubuntu Dockerfile
This repository contains Dockerfile of Ubuntu for Docker's automated build published to the public Docker Hub Registry.

Base Docker Image
ubuntu:latest
Installation
Install Docker.

Download automated build from public Docker Hub Registry: docker pull dockerfile/ubuntu

(alternatively, you can build an image from Dockerfile: docker build -t="dockerfile/ubuntu" github.com/dockerfile/ubuntu)

Usage
docker run -it --rm dockerfile/ubuntu
