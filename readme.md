## How to run it

* Make sure to have Docker installed in your computer
* Clone this repository
* Run `docker-compose up` for the first time you run the app because you will need to download the images, for subsequent startups of the app `docker-compose start` will do the trick

You should have the dockerized app running on port 8000

The environment uses the following images:
PHP 7.2
Mysql 5.7
Nginx
Composer


To run composer or artisan commands, follow this pattern: `docker-compose exec app <command>`

Example: `docker-compose exec app php artisan migrate`

It's recommended that you create an alias for `docker-composer exec app` to use as a shortcut