# e-commerce-website

[![License: MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project builds out the backend of an e-commerce website using mysql, mysql2, and Sequelize, with the help of dotenv to protect user database data within an environment variable file. It utilizes models to structure the mysql data and routes to get, create, update, and delete data within the database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)
- [License](#license)

## Installation

Make sure you have node.js installed to run the application. Navigate to the project directory and run 'npm i' to install package dependencies. You'll also have to create a .env file to hold your mysql login data. Lastly, since there's no front-end to the application, you'll need to install Insomnia to test the routes.

## Usage

Once you've navigated to the e-commerce-website directory in the command line, you'll need to open the mysql shell and run 'source db/schema.sql' to create the databse. Then from the command line, run 'npm run seed' if you'd like to seed the database with sample data. Finally, run 'node server.js' to start the application. Since there's no front-end built, you'll have to use Insomnia to test the routes.

Video Walkthrough: https://drive.google.com/file/d/1O2ryu7DUqSTP5oFcAnxx-8OaZqGvHi2f/view?usp=share_link 

## Questions

Feel free to submit pull requests at the repo or send me an email with any questions you have.

GitHub: https://github.com/zbeiser

Email: zbeiser@gmail.com

## License:
    
MIT License
    
