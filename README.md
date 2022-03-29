# FlaskRestApi

A framework is a code library that makes a developer’s life easier when building web applications by providing reusable code for common operations. There are a number of frameworks for Python, including Flask, Tornado, Pyramid, and Django. Flask is a lightweight web application framework. It is classified as a micro-framework because it does not require particular tools or libraries. Side tabs are used for single page web applications or to display different contents.

# Pre-requisite: 

Knowledge of Python, MySQL Workbench and basics of Flask Framework. Python and MySQL Workbench should be installed in the system. Visual studio code or Spyder or any code editor to work on the application.
Technologies used in the project: Flask framework, MySQL Workbench.

# Database

# MySQL Workbench

Step-1: Install MySQL workbench.

Link to install : https://dev.mysql.com/downloads/workbench/

Know more about it : https://www.mysql.com/products/workbench/

Step-2: Install ‘mysqlbd’ module in your venv.

# pip install flask-mysqldb

Step-3: Open MySQL workbench.

Step-4: Write the following code. The above SQL statement will create our database geekprofile with the table accounts.

Step-5: Execute below queries one by one.

create database geekprofile;

SELECT * FROM accounts;
create table if not exists `accounts`(
	`id` int(11) not null auto_increment,
    `username` varchar(50) not null,
    `password` varchar(255) not null,
    `email` varchar(100) not null,
    `organisation` varchar(100) not null,
    `address` varchar(100) not null,
    `city` varchar(100) not null,
    `state` varchar(100) not null,
    `country` varchar(100) not null,
    `postalcode` varchar(100) not null,
    primary key (`id`)
) engine=InnoDB auto_increment=1 default char set=utf8;
