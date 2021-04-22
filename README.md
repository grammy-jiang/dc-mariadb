# Docker Compose of MariaDB

A very simple docker-compose of MariaDB.

This repo is only used on my Raspberry Pi 3 with Ubuntu 18.04 (ARM64).

The root user is configured in `mariadb.env` and allowed to login from anywhere.

A user named `user` and its password `password` is created by
`initdb.d/createUser.sql`, the database for this user is named `user_db`.

# Reference

* [mariadb - Docker Hub](https://hub.docker.com/_/mariadb)
* [Installing and Using MariaDB via Docker - MariaDB Knowledge Base](https://mariadb.com/kb/en/installing-and-using-mariadb-via-docker/)
* [phpmyadmin - Docker Hub](https://hub.docker.com/_/phpmyadmin)
* [Installation — phpMyAdmin 5.2.0-dev documentation](https://docs.phpmyadmin.net/en/latest/setup.html#installing-using-docker)
