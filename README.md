# ![Laravel RealWorld Example App](.github/readme/logo.png)

[![RealWorld: Backend](https://img.shields.io/badge/RealWorld-Backend-blueviolet.svg)](https://github.com/gothinkster/realworld)
[![Tests: status](https://github.com/f1amy/laravel-realworld-example-app/actions/workflows/tests.yml/badge.svg)](https://github.com/f1amy/laravel-realworld-example-app/actions/workflows/tests.yml)
[![Coverage: percent](https://codecov.io/gh/f1amy/laravel-realworld-example-app/branch/main/graph/badge.svg)](https://codecov.io/gh/f1amy/laravel-realworld-example-app)
[![Static Analysis: status](https://github.com/f1amy/laravel-realworld-example-app/actions/workflows/static-analysis.yml/badge.svg)](https://github.com/f1amy/laravel-realworld-example-app/actions/workflows/static-analysis.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellowgreen.svg)](https://opensource.org/licenses/MIT)

> Example of a PHP-based Laravel application containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) API spec.

This codebase was created to demonstrate a backend application built with [Laravel framework](https://laravel.com/) including RESTful services, CRUD operations, authentication, routing, pagination, and more.

We've gone to great lengths to adhere to the **Laravel framework** community style guides & best practices.

For more information on how to this works with other frontends/backends, head over to the [RealWorld](https://github.com/gothinkster/realworld) repo.

## How it works

The API is built with [Laravel](https://laravel.com/), making the most of the framework's features out-of-the-box.

The application is using a custom JWT auth implementation: [`app/Jwt`](./app/Jwt).

## Getting started

The preferred way of setting up the project is using [Laravel Sail](https://laravel.com/docs/sail),
for that you'll need [Docker](https://docs.docker.com/get-docker/) under Linux / macOS (or Windows WSL2).

### Installation

Clone the repository and change directory:

    git clone https://github.com/f1amy/laravel-realworld-example-app.git
    cd laravel-realworld-example-app

Install dependencies (if you have `composer` locally):

Use link: https://docs.docker.com/engine/install/ubuntu/#set-up-the-repository

Create a Dockerfile and docker-compose.yml file

Run docker compose build && docker compose up -d

Feedback, suggestions, and improvements are welcome, feel free to contribute.

## License

The MIT License (MIT). Please see [`LICENSE`](./LICENSE) for more information.
