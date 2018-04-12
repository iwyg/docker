# Docker images for php, nodejs, etc.

[![Build Status](https://travis-ci.org/iwyg/docker.svg?branch=development)](https://travis-ci.org/iwyg/docker)

## PHP

### 7.1-cli

Image based on the official [php:7.1-cli-alpine](https://hub.docker.com/_/php/) image.

Extensions:

- amqp
- bcmath
- Core
- ctype
- curl
- date
- dom
- fileinfo
- filter
- ftp
- hash
- iconv
- igbinary
- intl
- json
- libxml
- mbstring
- mcrypt
- memcached
- mongodb
- mysqlnd
- openssl
- pcntl
- pcre
- PDO
- pdo_mysql
- pdo_pgsql
- pdo_sqlite
- Phar
- posix
- readline
- redis
- Reflection
- session
- SimpleXML
- soap
- SPL
- sqlite3
- standard
- tokenizer
- xml
- xmlreader
- xmlwriter
- zlib
- zmq


### 7.1-cli-xdebug

Image based on iwyg/php:7.1-cli

Extensions:

- xdebug


### 7.1-fpm

Image based on the official [php:7.1-fpm-alpine](https://hub.docker.com/_/php/) image.

Extensions:

- amqp
- bcmath
- Core
- ctype
- curl
- date
- dom
- fileinfo
- filter
- ftp
- hash
- iconv
- igbinary
- intl
- json
- libxml
- mbstring
- mcrypt
- memcached
- mongodb
- mysqlnd
- openssl
- pcntl
- pcre
- PDO
- pdo_mysql
- pdo_pgsql
- pdo_sqlite
- Phar
- posix
- readline
- redis
- Reflection
- session
- SimpleXML
- soap
- SPL
- sqlite3
- standard
- tokenizer
- xml
- xmlreader
- xmlwriter
- zlib
- zmq

### 7.1-cli-xdebug

Image based on iwyg/php:7.1-fpm

Extensions:

- xdebug

## Nodejs

### 9.11-yarn

Image based on the official [node:9.11-alpine](https://hub.docker.com/_/node/) image

This image packs in [yarn](https://yarnpkg.com) as node package manager.
