# Tech-Blog [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Screenshot (current progress)

<img width="1440" alt="Screen Shot 2021-07-30 at 11 24 13 PM" src="https://user-images.githubusercontent.com/70029654/127727420-37cfc7ad-adbf-42a3-aa6d-40136f673735.png">

## Description

A full stack web app that serves as a forum for users to post and comment on blog posts.

This application's structure follows the Model-View-Controller paradigm. It uses **_Handlebars.js_** for managing Views, **_MySQL2_** and **_Sequelize_** to connect to a MySQL database for the Models, and **_Express.js_** for the Controllers.

It also utilizes **_dotenv_** for environment variables, **_bcrypt_** - to hash passwords, and **_express-session/connect-session-sequelize_** for authentication.

## Table of Contents

- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [Tests](#Tests)
- [License](#License)
- [Collaboration](#Collaboration)

## Installation

### Dependencies: **Requires** **_Node.js_** installed on your computer

\
To install the npm dependencies cd into the main directory and run:

```
npm i

cd db && mysql -u root -p

source schema.sql

exit
```

## Usage

This site is live at heroku link!

To use this node app and create your own local server, clone the repo down, use the terminal to cd into the root directory. Then run:

```
npm start
```

Use the terminal and start up the server. You can then access the API endpoints through a web browser or Insomnia.

## Tests

To test please run:

```
npm test
```

## License

[MIT License](https://opensource.org/licenses/MIT)

## Collaboration

Please feel free to collaborate with me on this project! Just fork it and submit a well documented pull request.

If you have any questions, please contact me at techx@opayq.com
