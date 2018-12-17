[![Docker Stars](https://img.shields.io/docker/stars/practicalci/docker-debian-miniconda3.svg?style=flat-square)](https://hub.docker.com/r/practicalci/docker-debian-miniconda3/)
[![Docker Pulls](https://img.shields.io/docker/pulls/practicalci/docker-debian-miniconda3.svg?style=flat-square)](https://hub.docker.com/r/practicalci/docker-debian-miniconda3/)

Lightweight Debian image with Miniconda3. Docker image
==============================

This docker image used as a base for images that use conda environments.

Download size of this image is only:
[![](https://images.microbadger.com/badges/image/practicalci/docker-debian-miniconda3.svg)](http://microbadger.com/images/practicalci/docker-debian-miniconda3 "Get your own image badge on microbadger.com")


Docker Hub Build
----------------

This template assumes you to be registered in Docker Hub.
To setup automated build via Docker Hub refer to: [Set up Automated builds](https://docs.docker.com/docker-hub/builds/).

To configure automated builds follow this link [Build configurations](https://cloud.docker.com/u/practicalci/repository/docker/practicalci/docker-debian-miniconda3/builds/edit)


Usage Example
-------------

This image is intended to be a base image for your projects, so you may use it like this:

```
Dockerfile
    FROM practicalci/docker-debian-miniconda3

    COPY ./my_app /usr/local/bin/my_app
```

```
sh
    $ docker build -t my_app .
```

License
-------

This project is licensed under: [BSD-3-Clause](https://tldrlegal.com/license/bsd-3-clause-license-(revised))


Attributions
------------

Add below authors and licenses from which your work derives from, if any.

This work is derived from the work of:

| Author            | Work Source                                  | License                      |
|:------------------|:---------------------------------------------|:-----------------------------|
| Add Some Author   | <https://some-author-work-source-url>        | [some-author-license.txt](./attributions/some-author-license.txt) |
