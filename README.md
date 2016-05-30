# _PROJECT NAME_

#### SHORT DESCRIPTION, May 30, 2016

#### By **Inthrayuth Mahaphol**

## Description

DETAILED DESCRIPTION

## Setup/Installation Requirements

* Link to repository: https://github.com/inthra
* Clone or download this repository to your Github account
* Create a project directory on your computer
* Install Node.js on your computer
* In your terminal run "npm install", "bower install", "gulp build", and "gulp serve"
* A local web server should automatically open in your browser if you run "gulp serve". If you run "gulp build" only, you need to open a browser manually.

## Setup API Requirements

* Anyone who uses the app will need their own key in a local file with the same filename and location.

* Create a file in the top level of your project directory called .env (hidden file) to hold our API key. This is a common file extension for a configuration file used to set up environmental variables. Paste your API key in your .env file that you just created and store it in an exported property named apiKey.

* API key .env file example: **exports.apiKey = "YOUR-API-KEY";**

* In your JavaScript file that gets access to the API key, add the following requirement: **var apiKey = require('./../.env').apiKey;**

## Known Bugs

If a bug is found, please let me know via Github.

## Support and contact details

Feel free to contact me with questions or suggestions.

## Technologies Used

* Git and GitHub
* Atom text editor
* Html, CSS, Bootstrap
* JavaScript, jQuery
* Node.js - including npm and bower

### License

_This software is licensed under the MIT license_

Copyright (c) 2016 Inthrayuth M.
