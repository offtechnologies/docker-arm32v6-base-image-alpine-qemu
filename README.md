# Raspberry Pi 1 Alpine 3.6 Docker

[![Build Status](https://travis-ci.org/offtechnologies/docker-arm32v6-base-image-alpine-qemu.svg?branch=master)](travis-ci.org/offtechnologies/docker-arm32v6-base-image-alpine-qemu)
[![This image on DockerHub](https://img.shields.io/docker/pulls/offtechnologies/docker-arm32v6-base-image-alpine-qemu.svg)](https://hub.docker.com/r/offtechnologies/docker-arm32v6-base-image-alpine-qemu/)

[offtechurl]: https://offtechnologies.gthub.io

[![offtechnologies](https://raw.githubusercontent.com/offtechnologies/offtechnologies.github.io/master/logo.png)][offtechurl]

This base arm32v6 (Raspberry Pi 1) container is not aimed at public consumption. It exists to serve as a single endpoint for offtechnologies containers and is based upon Alpine 3.6 arm32v6 and qemu-arm-static binary. You are now able to build Docker images for ARM on ordinary cloud CI services that only provide Intel CPU’s.

## Credits

- [Resin.io's blog post](https://resin.io/blog/building-arm-containers-on-any-x86-machine-even-dockerhub/) Building arm containers on any x86 machine
- [Hypriot's blog post](https://blog.hypriot.com/post/setup-simple-ci-pipeline-for-arm-images/) Setup a simple CI pipeline for arm images
- Built with the [arm32v6/alpine](https://hub.docker.com/u/arm32v6/) base image

## 1.0.0 - 2017-10-30
* first release
