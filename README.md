# E-commerce Back End

The aim of this project was to build the back end for an e-commerce website that uses the latest technologies in order to be competetice with other e-commerce companies

## Table of Contents
[Technologies Used](#technologies-used) <br>
[Installation](#installation) <br>
[Usage](#use) <br>
[Testing](#tests) <br>
[Media](#media) <br>
[Questions](#questions) <br>

## Technologies Used
* express
* sequelize
* mysql
* JavaScript

with a focus on creating back-end models and routes

---

## Installation
Navigate to the root directory in the terminal and initialize the project with **npm install** to install all the proper node module dependencies.

Update the **.envExample** file to include your own username and password for mysql and then change the file name to be **.env** instead of .envExample

Navigate to the root directory in the terminal and log into mysql with **mysql -u &lt;user> -p** and enter your mysql password.

Initialize the database in mysql using the following commands
* **source db/schema.sql**

Exit mysql and run **npm run seed** in the terminal to populate the database

---

## Use
Navigate to the root directory in the terminal and type **npm start** to run the project.

---

## Tests
There are no official tests for this project

---

## Media
insert screenshot here
insert video here

The following link is to this project's github repository
https://github.com/p-fassbender/e-commerce-back-end

---

## Questions
Any questions feel free to contact me via [my github](https://github.com/p-fassbender) or by sending me an email at fassbenderp0551@gmail.com.

---

## USER STORY
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## ACCEPTANCE CRITERIA
* GIVEN a functional Express.js API
* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
* WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
* WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
* WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database