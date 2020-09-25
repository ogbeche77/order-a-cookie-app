# Project Name

> Order- A-Cookie

## Table of contents

- [General info](#general-info)
- [Technologies](#technologies)
- [How to run the app](#How-to-run-the-app)
- [Status](#staus)
- [Contact](#contact)

## General info

Order-A-Cookie was built using ReactJS, React hook and CSS on the front end. NodeJS, KnexJS & ExpressJS on the backend to manage orders. The database used to save orders is SQLite.
Night mode functionality was also implemented which prevents customers/visitors from ordering cookie.

## Technologies

- axios - version 0.19.2
- bootstrap- version 4.5.2
- react - version 16.13.1
- react-dom - version 16.13.1
- react-scripts - version 3.4.3
- cors - version 2.8.5
- express - version 4.17.1
- knex - version 0.21.5-next2
- nodemon - version 5.0.0
- sqlite3 - version 5.0.0

## How to run the app

1. Extract both the client and server folder to any folder of your choice.
2. CD into the client and run “npm install” without quotes to install all dependencies.
3. Then run “npm start” without quotes to start the application. The application will be served on localhost:3000. Visit http://localhost:3000 on your browser to load the application.
4. CD into the server folder and also run “npm install” without quotes to install all dependencies
5. Then run “node index.js” to start the server. (Ensure that client server is also still running on localhost:3000)
6. To view the database of ordered cookies after the door is knocked (clicked). Visit http://localhost:1337/api/order on the web browser.
   Although not necessary, JSON view extension can be enabled on the browser for better formatting of the database

## Status

Project is:completed

## Contact

Created by [@ogbeche77](https://github.com/ogbeche77)
