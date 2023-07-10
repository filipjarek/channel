# Channel-app
> A web application that allows you to CRUD customer journey channels and represent them based on a pie chart.

## Table of Contents
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Testing](#testing)

## Technologies Used
    
    Laravel 10.14.1
    PHP 8.2.0
    React 18.2.0
    React-chartjs-2 5.2.0
    Node.js 18.14.0
    npm 9.8.0
    TailwindCSS 3.3.2
    Sweet-alert 2.1.2
    Phpunit/phpunit 9.5.10
    Database MySQL
    
## Features
List the ready features here:
- Creating new channels, editing and deleting
- The data is saved in the database
- Preview of created channels on a pie chart
- There is a table displaying all channels with the sum of all customers

## Screenshots

## Setup
#### Step 1 : Clone the project
```
$ git clone https://github.com/filipjarek/channel
```
#### Step 2 : Change current directory
```
$ cd channel
```
#### Step 3 : Generate key
```
$ php artisan key:generate
```
#### Step 4 : Configuration
```
Copy .env.example file to .env on the root folder.
Set the database (mysql) in .env file db_name, db_username and db_password.
```
#### Step 5 : Install dependencies
```
$ composer install
$ npm install
$ npm run build / npm run dev
```
#### Step 6 : Setup database
```
$ php artisan migrate
```
#### Step 7 : Run the project
```
$ php artisan serve
```
Open link in your browser: http://localhost:8000:

## Testing

#### Backend
```
$ ./vendor/phpunit/phpunit/phpunit
$ php artisan test
```
#### Frontend
```
$ npm test
```
