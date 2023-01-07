# Clockit
This is a leave-management system, aimed at helping startups measure and manage employees leave for the year.

# Requirements
```sh
    "php": "^8.0"
```
# Setting it up
These are the steps to get the app up and running. Once you're using the app.

1. Clone the repository
2. `composer install`
3. Rename `.env.example` to `.env` and run `php artisan key:generate`
4. Create a MySQL database. Add the database name to your `.env`
5. Run migrations: `php artisan migrate --seed`
6. Run `php artisan test`
