<h1 align="center">Eat-da-Burger</h1>
  
[![license](https://img.shields.io/static/v1?label=license&message=MIT&color=yellow)](https://opensource.org/licenses/MIT)
  
  ## Description
  Eat-da-Burger was created with MySQL, Node, Express, Handlebars, and a homemade ORM. Node and MySQL were used to query and route data into the app, and Handlebars was used to generate the HTML. This is a restaurant app that lets users input the names of the burgers they'd like to eat. Whenever a user submits a burger's name, the app will display the burger on the left side of the page - waiting to be devoured. Once the user devours the burger, it is moved to the right side of the page - where it will wait to be deleted. All burgers are stored into the database, whether devoured or not. 

  ## Table of Contents
  - [Description](#description)
  - [Demo](#demo)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributors](#contributors)
  - [Tests](#tests)
  - [License](#license)
  - [Technologies](#technologies)
  - [Questions](#questions)
  
  ## Demo
  ![Application Preview](assets/Demo.gif)
  
  To view the full application, please direct yourself to the following link: https://damp-oasis-62499.herokuapp.com/
  
  ## Installation
  Eat-da-Burger requires the installation of Express, MySQL, and Handlebars from npm to run properly in a local dev environment. To install the project's npm dependencies, navigate to the project's root directory and run:

  ```
  npm i
  ``` 
 
 
  Once all third-party packages have been successfully installed, the application is ready to use. For more details, reference the application's ```package.json``` file.
  
  ## Usage
  To launch the application from the command line, navigate to the project's root directory and run:
  ```
  node server.js
  ```
  The application begins by prompting the user to enter the name of a new burger. Once the user places their order, that burger is shown on the left side of the app with a devour button. The user can click the devour button and that burger will move to the right side of the app. From there, the user can delete the burger from the application and from the database.  
 
  ## Contributors
  Emily B. Todt
 
  ## Tests
  No tests were included.
  
  ## License
        Copyright (c) 2021 Emily B. Todt 
        Licensed under the [MIT license](https://opensource.org/licenses/MIT).
  
  ## Technologies
  JavaScript, Node.js, MySQL, HTML, CSS, Handlebars, Express
  
  ## Questions
  Reach me on [GitHub](https://www.github.com/todtsies)  
  Reach me via email at <emilybtodt@gmail.com>