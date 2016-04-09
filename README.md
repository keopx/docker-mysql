# Introduction #

This image works with **Debian 8** and use current last **MySQL 5.5** version.

## Example usage: ##

`$ docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=change_me keopx/docker-mysql`

## Environment variables ##

* MYSQL_ROOT_PASSWORD: The password for the root user. Defaults to a blank password
* MYSQL_DATABASE: A database to automatically create. If not provided, does not create a database.
* MYSQL_USER: A user to create that has access to the database specified by MYSQL_DATABASE.
* MYSQL_PASSWORD: The password for MYSQL_USER. Defaults to a blank password.
