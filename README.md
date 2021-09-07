docker-php74-fpm
================

This repository contains a Dockerfile of PHP 7.4 FPM for Docker's automated build published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

### Installation

1. Install [Docker](https://www.docker.com/).

2. Download the [automated build](https://registry.hub.docker.com/u/uqlibrary/php74-fpm/) from the public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull uqlibrary/php74-fpm`

   (or, you can build an image from Dockerfile: `docker build -t uqlibrary/php74-fpm`)

### Usage

1. Start the container:

    ```sh
    docker run uqlibrary/php74-fpm
    ```

