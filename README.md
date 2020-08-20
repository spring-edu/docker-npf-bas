# docker-npf-base

docker build -f Dockerfile -t magicgear/nginx-php-fpm:latest .

docker pull magicgear/nginx-php-fpm

docker run -it --rm magicgear/nginx-php-fpm:php7.4-node14 bash
