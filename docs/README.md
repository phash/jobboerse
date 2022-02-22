Jobboerse Module - a fork of tasks (https://github.com/humhub/tasks)
==============

Simple task manager for spaces - but with tracking of working hours


Installation:

docker run -d --name humhub_db -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=humhub mariadb:10.2
docker run -it --volume m:/dock/module:/var/www/localhost/htdocs/protected/modules --name hum -p 80:80 --link humhub_db:db mriedmann/humhub:latest

