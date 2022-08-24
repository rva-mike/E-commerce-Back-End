
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  # E-commerce Back-End

  ## Description
  This application is the back end for an e-commerce site. It uses an Express.js API and configures it to use Sequelize to interact with a MySQL database. Data of products, categories, and tags can all be stored, edited, and deleted.

  ## Table of Contents
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Questions](#questions)

  ## Installation
  Git clone this repository. Install the node packages with the command 'npm i'. Make sure you have MySQL 12 and Sequelize downloaded. Add an .env file to the root of the app with the following. 
    
    DB_NAME='ecommerce_db'
    DB_USER='root'
    DB_PW='your password goes here'

    Then, login to MySQL (mysql -u root -p). Add the schema with the command 'db/schema.sql' Quit MySql with the command 'quit'. Add your own seeds or use the command 'npm run seed' for starter data. Finally, run the command 'node server'. Use an application like 'Insomnia' to test locally using http://localhost:3001/.
    


  ## Usage
  Used for managing a e-commerce business product database. 

  ## License
  MIT

  https://opensource.org/licenses/MIT


  ## Questions
  Please send me an email or visit my GitHub profile if you need to reach me for additional questions.

  Email: mike.levy.rva@gmail.com

  GitHub Profile: https://github.com/rva-mike

