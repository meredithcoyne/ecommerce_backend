# E-commerce Backend
![MIT License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)
## Description
---------
Build the backend for an e-commerce site that works with Express.js and interacts with MySQL database, JSON, Sequalize, and Insomnia

## Table of Contents
-----
 * [Installation](https://github.com/meredithcoyne/ecommerce_backend#Installation)
 * [Usage](https://github.com/meredithcoyne/ecommerce_backend#Usage)
 * [Resources](https://github.com/meredithcoyne/ecommerce_backend#Resources)
 * [Demo](https://github.com/meredithcoyne/ecommerce_backend#Demo)
 * [Questions](https://github.com/meredithcoyne/ecommerce_backend#Questions)
 * [License](https://github.com/meredithcoyne/ecommerce_backend#License)
  
## Installation
------
1. Download or clone repository.
2. Node.js is required to run the application
3. `npm install` to install the required npm packages
4. `npm install sequelize` to install sequelize
5. `npm install mysql2` to install mysql2
6. Open MYSQL and enter schema with live host to create a database to connect.
7. `npm run seed` be entered into your terminal after the .env file is inputted.
8. Run `npm start` to run the localhost:3001


## Usage
------
* In order for the application to run, MySQL must be installed in your environment. Then, from the root folder, enter the sql shell and run the following commands.

    [scheme.sql](/db/schema.sql)

* Exit the sql shell and return to the command line still within your root project folder.

* Run the following commands
  
    *  `npm run seed`

    * `npm start`

  *  ### DB START
    ![DB START](assets\db.gif)

  
  
  
  *  ### TAGS Routes
    ![POST PUT DELETE TAGS](assets\TAG.png)

    
     *  ### PRODUCTS Routes
    ![POST PUT DELETE PRODUCTS](assets\Products.png)

   *  ### CATEGORIES Routes
    ![POST PUT DELETE CATEGORIES](assets\Category.png)
  
## Resources
------
* JavaScript
* Node.js
* MySQL
* npm packages to install

## Demo
------
[Ecommerce Backend](https://youtu.be/JTb3So3zhE4)


## Questions
  ------
  For any questions, please contact me via github or e-mail. 

  * Checkout my [GitHub Repository](https://github.com/meredithcoyne/ecommerce_backend)
  
  * Any additional questions or feed back, feel free to [send an email](mailto:meredithleigh.coyne@gmail.com). 

  ## License
  Copyright 2021 Meredith Coyne

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

