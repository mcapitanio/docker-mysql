# **MySQL**
___

### Description

This image runs [*MySQL*](https://www.mysql.com).

You can pull the latest image it with:

    docker pull parrotstream/mysql


You can also find other images based on different MySql releases, using a different tag in the following form:

    docker pull parrotstream/mysql:[mysql-release]


For example, if you want MySql release 5.6 you can pull the image with:

    docker pull parrotstream/mysql:5.5


Run with Docker Compose:

    docker-compose up

### Available tags:

- MySQL 8.0 ([8.0](https://github.com/parrotstream/docker-mysql/blob/8.0/Dockerfile), [latest](https://github.com/mcapitanio/docker-mysql/blob/latest/Dockerfile))
- MySQL 5.7 ([5.7](https://github.com/parrotstream/docker-mysql/blob/5.7/Dockerfile))
- MySQL 5.6 ([5.6](https://github.com/parrotstream/docker-mysql/blob/5.6/Dockerfile))
- MySQL 5.5 ([5.5](https://github.com/parrotstream/docker-mysql/blob/5.5/Dockerfile))

