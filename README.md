<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.



## Table of Contents
- [About this application](#about-this-application)
- [Laravel Vue JS CRUD Application (SPA) :](#laravel-vue-js-crud-application-spa-)
- [Server Requirements](#server-requirements)
- [1. Install Laravel Project](#1-install-laravel-project)
- [2. Configure Database Details:](#2-configure-database-details)
- [3. Install NPM Dependencies](#3-install-npm-dependencies)
---







# About this application
CRUD app with laravel and vuejs

In this Laravel Vue.js Crud app, we will implement Laravel Vue.js crud (create, read, update, and delete) spa (Single Page Application) with Vue.js, Vue Router, and Laravel Framework.

In today's, the most popular JS frameworks are Angular JS and Vue JS. Angular JS and Vue JS are very user-friendly JS frameworks and most popular. It provides to manage the whole project or application without refresh page and powerful jquery validation.

Vue comes pre-packaged with Laravel (along with Laravel Mix, an excellent build tool based on webpack) and allows developers to start building complex single-page applications without worrying about transpilers, code packaging, source maps, or any other 'dirty' aspects of modern frontend development.


- [Laravel Vue JS CRUD Application](https://techvblogs.com/blog/build-crud-app-with-laravel-and-vuejs).

# Laravel Vue JS CRUD Application (SPA) :

  1. Install Laravel Project
  2. Configure Database Details
  3. Install NPM Dependencies
  4. Create Migration, Model, and Controller
  5. Define Routes In web.php
  6. Create a Vue App
  7. Create Component For Vue App
  8. Define Route For Crud App in Vue Router
  9. Include Vue.js Dependencies to app.js
  10. Update webpack.mix.js
  11. Run Development Server

# Server Requirements

PHP 7.4

Laravel 8.x

MySQL

# 1. Install Laravel Project

First, open Terminal and run the following command to create a fresh laravel project:

    composer create-project --prefer-dist laravel/laravel crud-spa

or, if you have installed the Laravel Installer as a global composer dependency:

    laravel new crud-spa

# 2. Configure Database Details:

After, Installation Go to the project root directory, open .env file, and set database detail as follow:

    DB_CONNECTION=mysql 
    DB_HOST=127.0.0.1 
    DB_PORT=3306 
    DB_DATABASE=<DATABASE NAME>
    DB_USERNAME=<DATABASE USERNAME>
    DB_PASSWORD=<DATABASE PASSWORD>

# 3. Install NPM Dependencies

Run the following command to install frontend dependencies:

    npm install

Next, install vue, vue-router and vue-axios. Vue-axios will be used for calling Laravel backend API. Run the following command on the terminal:

    npm install vue vue-router vue-axios --save