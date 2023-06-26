﻿# Docker_CodeIgniter_Test
 This mini-project will demonstrate how docker works with the Codeigniter framework.
1. Make sure you already install docker on your computer.
2. Clone this project
3. Run "docker-compose up -d" OR "docker-compose up" command to build docker container and start all services inside the docker-compose.yml file.
From now all services have been started, and you can access http://localhost:8000/ to see whether it works.
When you access http://localhost:8000/index.php/Register_controller you will see a registration form to register a new user.
To check the new user you regist above, go to phpmyadmin to check if data is exists (http://localhost:8081/index.php, Username: root, Password: root, Database: ciapp)

To stop docker container run "docker-compose stop" command.
To permanently delete docker container run "docker-compose rm" command.

P/s: Inside the folder "scripts" there is a sql file (initdb.sql), you can use this file as a seeding database for your project and you can changes to anything you want
