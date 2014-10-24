POS-ws-server
=============

Websocket backend server for Next Gen POS

## Demo

site = http://pos.jawait.net

user = admin

pass = admin

## Requirements
 - [`Composer`](https://getcomposer.org/)
 - [`Propel ORM`](http://propelorm.org/)
 - [`Memcache`](http://memcached.org/)
 - [`Zero MQ`](http://zeromq.org/)
 - Httpd server (nginx, apache atau lainnya)
 - MariaDB atau MySql
 - PHP 5.4 +
 
## Frontend Repository
 
 [`POS - Next Generation Point Of Sale Application`](https://github.com/nicklaros/POS)
 
# Setting Up Project
 
 - Clone or fork POS-ws-server to your computer
 - Use `composer update` command in POS-ws-server root directory to tell composer to gather 
   required repository for you
 
# Running the Server
 
 Go to POS-ws-server root directory and use the following command
 
 ```bash
$ php bin/server.php
```