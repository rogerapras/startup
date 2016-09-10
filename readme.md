## StartUp 5.3

<img src="https://raw.githubusercontent.com/w00p/startup/master/public/uploads/readme.png" alt="StartUp 5.3">

StartUp 5.3 is a Open Source StartUp Boilerplate built with Laravel 5.3. It is built with the awesome Laravel Framework. It includes roles & permissions,
user profile,admin backend and much more.

## Features

* Laravel 5.3
* Register/Login/Logout/Password Reset
* Authentication/Users/Roles/Permissions
* Administrator Management
* Change/Create/Manage Users/Roles/Permissions
* Default Responsive Layout
* Frontend and Admin Controllers
* Bootstrap 3
* Font Awesome
* Upload Avatar
* Activity log
* User e-mail activation.
* Backup SQL database from admin settings section.
* File Uploads

## Requirements

Before you proceed make sure your server meets the following requirements:

- [Composer](https://getcomposer.org/)
- [PHP](https://php.net/) >= 5.6.4
- PDO compliant database (SQL, MySQL, PostgreSQL, SQLite)

## How to Install

1. Clone this repository: ```git clone https://github.com/w00p/startup.git ``` 
2. If you want to specify wich folder to clone to use: ```git clone <project url> my-folder```
3. ```composer install```
4. Create .env file (.env.example included, just copy that one to .env)
5. ```php artisan key:generate```
6. ```php artisan migrate --seed```
9. Thats it, visit your URL. Log in with one of the users below.

## Default Seeded Users

1. Admin role: admin@example.com / 12345678
2. Moderator role: moderator@example.com / 12345678
3. User role: user@example.com / 12345678

All new user registered is getting default User role.

## Packages used

* [spatie/laravel-permission](https://github.com/spatie/laravel-permission)
* [laravelcollective/html](https://laravelcollective.com/docs/5.3/html)
* [intervention/image](https://github.com/intervention/image)
* [spatie/laravel-activitylog](https://github.com/larapack/config-writer)
* [larapack/config-writer](https://github.com/spatie/laravel-activitylog)
* [spatie/db-dumper](https://github.com/spatie/db-dumper)
* [dflydev/dflydev-apache-mime-types](https://github.com/dflydev/dflydev-apache-mime-types)

## Screenshots
comming soon..

## Changelog

Detailed changes for each release are documented in the [release notes](https://github.com/w00p/startup/blob/master/CHANGELOG).

## License

StartUp 5.3 is open-sourced software licensed under the [MIT license](https://github.com/w00p/startup/blob/master/LICENSE).
