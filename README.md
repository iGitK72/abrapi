<h2 align="center"><a href="https://innovatorsandbox.com" target="_blank">Laravel Breeze API Project</a></h2>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About

This Laravel Breeze Project is a basic implementation of the Breeze starter kit from Laravel. This is only the API implementation with no UI elements included. Laravel Sanctum is used for Authentication.

Read more about Laravel below:

-   [Simple, fast routing engine](https://laravel.com/docs/routing).
-   [Powerful dependency injection container](https://laravel.com/docs/container).
-   Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
-   Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
-   Database agnostic [schema migrations](https://laravel.com/docs/migrations).
-   [Robust background job processing](https://laravel.com/docs/queues).
-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications. Breeze scaffolds Laravel as your back-end API.

## How to use

Clone this repo to your local machine.
Change directory into the root folder of the repo ie. `cd abrapi`
Install - Run `composer install`
Create env file - `cp .env.example .env`
Generate application key - `php artisan key:generate`
Configure env vars - Edit the .env to use sqlite as the database, and your local dev environment for the frontend consuming these API endpoints.  
`DB_CONNECTION=sqlite`
`SESSION_DOMAIN=127.0.0.1`
`SANCTUM_STATEFUL_DOMAINS='localhost,localhost:8000,localhost:3000,127.0.0.1,127.0.0.1:5173,127.0.0.1:8000,::1'`
Install database - `touch database/database.sqlite`
Migrate database - `php artisan migrate`
Start the local server - `php artisan serve`

Now the front-end can be started. For local dev it is expected to be run on 127.0.0.1:5173

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
