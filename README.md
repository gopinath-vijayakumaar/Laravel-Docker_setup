# Laravel-Docker_setup

To get this started we use 'composer', Install composer in working environment
After installing composer move composer in dir '/usr/local/bin/composer'
Create project using laravel - $ composer create-project laravel/laravel 'app name'

"Only laravel Version 8 provides docker function""

Now can run webserver in local- $php artisan serve


**Run laravel server inside docker**

Install docker desktop and run
To up and run server inside docker we use docker-compose as .yml
When project is created it will automatically create docker compose file in app dir.
To configure required tools we can write Dockerfile.
Use SAIL to run dockerfile wrote.
Install sail -composer require laravel/sail --dev
$php artisan sail:install
select required tools for application

Now in docker desktop check tools required for application running inside containers for application.





