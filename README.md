# deploy_symfony

Required : PHP, Composer and MySQL

Composer install

Example for apache web server put the vhosts.conf in /etc/apache2/sites-enabled/

Don't forget to restart your apache server

Change the env variable with your database credentials

Create the database
php bin/console doctrine:database:create
php bin/console make:migration:migrate