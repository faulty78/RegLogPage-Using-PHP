# Registration and Login Page

## Overview

This project is a simple registration and login system built using PHP. It allows users to register with a username and password, and then log in with their credentials. The system uses phpMyAdmin for database management.

## Features

- User registration with validation
- User login with session management
- Basic error handling

## Requirements

- XAMPP (or any other local server environment)
- PHP 7.0 or higher
- MySQL
- phpMyAdmin

## Installation

### Step 1: Install XAMPP

Download and install XAMPP from the [official website](https://www.apachefriends.org/index.html).

### Step 2: Clone the Repository

Clone this repository to your local machine using:
`git clone https://github.com/faulty78/RegLogPage-Using-PHP.git`


### Step 3: Move to the 'htdocs' Directory

Copy the cloned repository to the 'htdocs' directory of your XAMPP installation. For example:

- Windows: 'C:\xampp\htdocs\RepLogPage-Using-PHP'
- macOS: '/Applications/XAMPP/htdocs/RepLogPage-Using-PHP'
- Linux: '/opt/lampp/htdocs/RepLogPage-Using-PHP'

### Step 4: Start Apache and MySQL

Open the XAMPP Control Panel and start the Apache and MySQL modules.

### Step 5: Create the Database

1. Open phpMyAdmin by navigating to **'http://localhost/phpmyadmin'** in your web browser.
2. Create a new database named **'userdb'**.
3. Import the **'tutorial.sql'** file located in the database folder of this repository to create the necessary tables.


### Step 6: Configure the Database Connection

Open the **'config.php'** file in the project directory and configure the database connection settings:

`<?php
   $host = 'localhost';
   $dbname = 'userdb';
   $username = 'root';
   $password = '';
   ?>`

Replace the values with your actual database credentials if they are different.

Open your Chrome Enter **'http://localhost/RepLogPage-Using-PHP/'**

## Screenshots

### Login Page:

![Login](https://github.com/faulty78/RegLogPage-Using-PHP/assets/102469530/c31ea245-3c35-4587-936c-566a055e0f69)

### Registration Page:

![Registration](https://github.com/faulty78/RegLogPage-Using-PHP/assets/102469530/c36e8816-5188-42bc-a3ec-36e9de8470b5)

### Home Page:

![Home](https://github.com/faulty78/RegLogPage-Using-PHP/assets/102469530/ca0283a8-acf7-4530-b568-c97cdd70dacb)
