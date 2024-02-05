# update vendors
composer install

# create database
php ./bin/console doctrine:database:create

# start application
symfony server:start

# api documentation
http://127.0.0.1:8000/api/docs?ui=re_doc