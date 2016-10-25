# Supported tags and respective `Dockerfile` links

* `java8`, `latest`, 8u111 [(Dockerfile)](https://github.com/moss-it/docker-java_oracle/blob/latest/Dockerfile)


# Base Docker Image

* [debian:8](https://registry.hub.docker.com/_/debian/)

# Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/moss/java_oracle/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull moss/java_oracle`

### Usage

    docker run -it --rm moss/java_oracle

#### Run `java`

    docker run -it --rm moss/java_oracle java

#### Run `javac`

    docker run -it --rm moss/java_oracle javac

