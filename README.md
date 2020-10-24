GeeksHubs Backend Practice Final - Showcase with express API with CRUD on Mongodb

## Features

In this practice we will use ESMAC6, drag&drop, Scss and responsive layout for to develop a showcase with you car of selection products.
Also, I will use, in back, server express to create API with CRUD connect its with Mongodb 

## Requirements

Please, run `npm i` to install all necessaries dependencies.

Also, cd into /server-express and run `npm i` to install all necessaries dependencies.

For run MongoDB, you have two options:

1.- You could have a installation of MongoDB in local and configure the port 27018
(See de file `./server-express/config/mongoose.js`)

OR

2.- You could have a Docker in local and exceute the next commands
`cd server-express`
`docker-compose -f docker-compose.yml up` 

When you launch server-express, the app and they are ok, you need register to access to showcase.

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits, only on sheetstyle files or javascript files.
If you do some modification in html, please reload the browser page

### `npm run build:dev`

Builds the app for development to the `dist` folder.<br />

### `npm run build`

Builds the app for production to the `dist` folder.<br />

### `npm clean`

Delete folder `dist`<br />
IMPORTANT: if you SO is windows, please replace in package.json the line scripts->clean to `rd dist`
