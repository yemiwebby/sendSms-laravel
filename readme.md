## Send SMS in a Laravel Application
Send SMS within a Laravel Application. (Check [Here](https://medium.com/techtrument/send-sms-from-laravel-application-d3ac9d1a4fac) for the complete tutorial)

### Getting Started
Clone this repository

```bash
git clone https://github.com/yemiwebby/sendSms-laravel.git
```

### Change Directory
```bash
cd sendSms-laravel

```

### install all dependencies
```bash
composer install 

```

##### Copy .env.example to .env

```bash
cp .env.example .env
```

##### Generate Application secure key (in .env file)
```bash
php artisan key:generate
```


### Database Connection Setup
Create a database and update .env file with database credentials

```bash

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=Your-database-name
DB_USERNAME=Your-database-username
DB_PASSWORD=Your-database-password

```

### Run migrations
```bash

php artisan migrate

```
### Serve the Application
```bash
php artisan serve

```