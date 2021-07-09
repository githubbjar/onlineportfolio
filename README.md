# Online Portfolio
The process: Completed Tutorials

## Table of contents
* [Steps](#step-1)
* [Technologies](#technologies)
* [Purpose](#purpose)

## 1: Point to Digital Ocean Nameservers 
* https://www.digitalocean.com/community/tutorials/how-to-point-to-digitalocean-nameservers-from-common-domain-registrars

## 2: Connect with SSH 
* https://docs.digitalocean.com/products/droplets/how-to/connect-with-ssh/

## 3: Initial Server Setup with Ubuntu 20.04 
* https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-20-04

## 4: Install LEMP Stack 
* https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-on-ubuntu-20-04
* NOTE: https://www.digitalocean.com/community/questions/nginx-server-unable-to-start-up-due-to-issues-with-conf Change sites-enabled to sites-available in config file

## 5: Install Composer 
* https://www.digitalocean.com/community/tutorials/how-to-install-and-use-composer-on-ubuntu-20-04

## 6: Install Docker 
* https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04
* NOTE: I had to confirm my docker account before I could see my pushes

## 7: Install and Set Up Laravel
*  https://www.digitalocean.com/community/tutorials/how-to-install-and-set-up-laravel-with-docker-compose-on-ubuntu-20-04
* NOTE: "docker-compose exec app composer install" would throw an error. I had to run "docker-compose exec app composer update laravel/framework" first. Then the first command ran fine.

## Technologies
Project is created with:
* Ubuntu 20.04.2
* Nginx/1.18.0
* MySQL 8.0.25-0
* PHP 7.4.3
* Composer 
* Docker 
* Larvel Framework 6.18.13
	
## Purpose
* Display my personal online portfolio using Laravel and hosting it (Digital Ocean) using a custom configuration 

```
https://github.com/githubbjar/onlineportfolio
```