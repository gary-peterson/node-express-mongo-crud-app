
# Node.js Express Mongo CRUD Example App

## Overview

A streamlined example to demonstrate:

- Node.js
- Express
- Mongo document-oriented No-SQL database
- Mongoose
- Static resources (css and img)
- EJS
- Partials (View)
- CRUD (Create, read, update and delete / post, get, put, delete)
- DB Search
- Validation
- Basic functionality (not artistic by any means)

## Prerequisites

The following must be installed

- Node.js
- Mongo

No project database initialization is required -- the app will create and initialize the db when it starts. 

## Running App

```
1. Download archive "node-express-mongo-crud-app.zip" and extract project dir
2. Open console and go to project dir
3. Run ">npm install"
4. Run ">node main"
5. Open a web browser to address "http://localhost:3000/"
```

## Directories

- / - project root (main.js and package files)
- /middlewares - middleware/controller logic
- /models - model source files / database logic
- /public - static sources (e.g., css, img, js)
- /views - view source files

## Code

The code is hopefully self-explanatory, but here are a few key touch points.

First is "main.js" which is a lightweight app entry point.

The following sub-sections describe some key elements in project dirs.

### models

- AppStartupTools - app initialization

- DbConnector - db initialization

- def.js - structure and behaviors for Def (a quick definition)

### routes

Contains the logic to route URL's to middleware (functional endpoints)

### middlewares

Contains the middleware functionality that is mapped/called by the routes

- common cases
- def (quick definition object)
- defs (collection of quick definition objects)
- search

### views

Contains the EJS HTML-template files for "def" objects and "defs"





