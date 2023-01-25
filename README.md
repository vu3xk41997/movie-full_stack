# movie-full_stack
Freecodecamp: Full Stack Development with Java Spring Boot, React, and MongoDB

## Backend
* Retrieve data as .json
* Create cluster on MongoDB and connect to MongoDB compass
* Generate source code with Java from Spring Initializr
* Impliment Java code to connect to MongoDB
* Retrive data from MongoDB
* Get data with Postman through localhost
* Post review with Postman into database

## Frontend
* Create React project with <code>npx create-react-app projectname<code/>
* Delete App.test.js, reportWebVitals.js, setupTest.js
* Remove eslint setting from package.json and reportWebVitals from index.js
* Install axios, bootstrap, @mui/material, @emotion/react, @emotion/styled, react-material-ui-carousel
* npm i to install relavent packages: react-bootstrap, @fortawesome/react-fontawesome, @fortawesome/free-solid-svg-icons, react-player, react-router-dom
* In index.js <code>import 'bootstrap/dist/css/bootstrap.min.css';<code/>
* Add src/api/axiosCongif.js, import axios and create baseUrl as backend port (localhost:8080)
* To prevent CORs, add <code>@CrossOrigin(origins = "http://localhost:3000")<code/> in both MovieController and ReviewController class
* Make sure to run Backend before running React
* Implement React with Bootstrap