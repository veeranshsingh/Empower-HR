# Empower-HR: World's Best Employee Management System


## Overview
An employee management system consisting of crucial work-related and important personal information about employees. Human Resources (HR) can manage their employees efficiently using this web application.

## Purpose
I created an online employee management system web application that will allow users can add, edit, update, search and delete employees. It will also allow Admin update code and assigned sections using an Admin dashboard (Admin page will be implemented in the future).

## Functionalities:

**1. Add employee information:** <br />
&nbsp; &nbsp; * Name <br />
&nbsp; &nbsp; * Profession <br />
&nbsp; &nbsp; * Color <br />
&nbsp; &nbsp; * City <br />
&nbsp; &nbsp; * Branch <br />

**2. Edit and Delete:** <br />
 Be able to edit and delete employees from the database. An employee's details are automatically populated when the user clicks the edit button

**3. Search:** <br />
 Be able to search (an) employee(s) by their first name, last name, and full name

**4. Display employees:** <br />
 Be able to retrieve employees from a REST API and display them
 


## Used technologies:
&nbsp; &nbsp; * React <br />
&nbsp; &nbsp; * Node.js <br />
&nbsp; &nbsp; * Express <br />
&nbsp; &nbsp; * MySQL <br />
&nbsp; &nbsp; * React-Table <br />
&nbsp; &nbsp; * React-Bootstrap <br />
&nbsp; &nbsp; * Axios <br />
&nbsp; &nbsp; * Cors <br />
&nbsp; &nbsp; * Nodemon <br />
&nbsp; &nbsp; * Styled-components <br />


## How to run:

&nbsp; &nbsp; 1. npm install <br />
&nbsp; &nbsp; 2. npm start <br /><br />

The front-end app runs on localhost:3000. The REST API is located in the /server folder and runs on localhost:8080. The data is being served by index.js located n the /server/index.js and actual data from  MySQL is located in the /server folder (if it does not exist, it will be created when the application is run for the first time). Run "npm start" to start both servers.
