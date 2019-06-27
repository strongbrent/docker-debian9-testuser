# Debian 9 (Stretch)

[![Build Status](https://travis-ci.org/strongbrent/docker-debian9-testuser.svg?branch=master)](https://travis-ci.org/strongbrent/docker-debian9-testuser) [![Docker Automated build](https://img.shields.io/docker/cloud/automated/strongbrent/docker-debian9-testuser.svg)](https://cloud.docker.com/repository/docker/strongbrent/docker-debian9-testuser) [![Docker Automated build](https://img.shields.io/docker/cloud/build/strongbrent/debian9-testuser.svg)](https://cloud.docker.com/repository/docker/strongbrent/docker-debian9-testuser/builds)

## Background
Stock Debian 9 (Stretch) Docker image with a default user for automation testing.

## How to Build this Image

This image is built automatically on Docker Hub any time a commit is made or code is merged to the `master` branch. However, if you need to need to manually build an image on your workstation, execute the following:
```
make image
```

## How to Run this Container

To run a container from this image, run this command:
```
make run
```

## How to Clean Up
To remove both the local container and image, run this command:
```
make clean
```

## Disclaimer 

This image is used to test build automation scripts. It is most definitely not suitable nor secure enough to run in any production environment.
