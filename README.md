# Laravel Installation and Setup Guide

First of all we have to install composer to start a project with laravel. To download composer [click here](https://getcomposer.org/download/). After installing the composer now create a laravel project by this commands :
```
composer create-project laravel/laravel example-app
cd example-app
php artisan serve
```

## To use authentication system in laravel 8
- Install the Laravel UI package
```
composer require laravel/ui
```
- Generate auth scaffolding
```
php artisan ui vue --auth
```
- Install NPM dependencies
```
npm install
```
- To compile assets run the command npm run dev
```
npm run dev
```

### Test the authentication system
```
http://127.0.0.1:8000/login
```
