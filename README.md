############################
Steps to Configure
############################

Laravel 
-------

	1. unzip laravel
    2. composer update
	3. Copy  ".env.example" to ".env"
	4. Create a new database, for configuring DB run command "php artisan set:credentials" 
	5. "php artisan key:generate"
	6. "php artisan migrate"
	7. "php artisan db:seed --class=RoleSeeder"
	8. "php artisan db:seed"

React
-----

    1. unzip React
    2. npm install
    3. npm start