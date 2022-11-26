# How to run using docker.

## Windows
    docker run --rm --name foodfully -p 80:80 -v %cd%:/var/www/html/ php:7.2-apache
## Linux
    docker run --rm --name foodfully -p 80:80 -v /$(pwd):/var/www/html/ php:7.2-apache