docker.ubuntu-apache-php-postgres_client
========================================

Docker image - ubuntu with apache, php and postgres client libs

usage:
 docker build -t="ubuntu-apache-php-postgres_client" .

 docker run -v `pwd`:/var/www/html -p 80:80 -d buntu-apache-php-postgres_client
