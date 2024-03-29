<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About LaravelHotel

laravel hotel booking system in feb 2021

- [Tahani Alhammad linkedIn ](https://www.linkedin.com/in/tahanialhammad/).
- [Tahani Alhammad Behance ](https://www.behance.net/tahani-ali-alhammad).

Laravel is accessible, powerful, and provides tools required for large, robust applications.


### Premium Partners

- **[CodGorilla](https://codegorilla.nl/)**
- **[Tailwindcss](https://tailwindcomponents.com/)**



## Code Steps
-  composer create-project laravel/laravel laravelhotel
- composer install
- npm install
- create database laravelhoteldb;
- /db config
- php artisan migrate
- /seeding
- composer require laravel/breeze --dev
- php artisan breeze:install
- npm install && npm run dev
- php artisan migrate:fresh
- php artisan make:model Room -fm
- php artisan make:controller RoomController --model="Room"
- php artisan make:model Reservation -fm
- php artisan migrate:fresh --seed
- composer dump-autoload
