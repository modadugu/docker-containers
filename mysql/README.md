# mysql container creation

### Instalation Guide

* Create tables in CreateTable.sql
* Load data as needed in InsertData.sql
* $ cd ~/mysql/    $ vi Dockerfile
* Create your docker image "docker build -t my-mysql ."
* Start your mqsql container "docker run -d -p 3306:3306 --name mysql \-e MYSQL_ROOT_PASSWORD=supersecret mysql"
* docker exec -it mysql bash
* mysql -uroot -p
