# Eat-Da-Burger App

## Overview

* I created a burger logger with MySQL, Node, Express, and Handlebars. 
* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat. Whenever a user submits a burger's name, the app displays the burger on the left side of the page -- waiting to be devoured.
* Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger moves to the right side of the page-- the devoured section.
* The app stores every burger in a database, whether devoured or not.

## Directory structure
```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
        
## Live App
* Click on the link to add some burgers to the menu! 

## Technologies Used
* Javascript
* CSS
* Bootstrap
* Node.js
* MySQL
* Handlebars.js
* Express.js
