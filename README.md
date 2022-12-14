# 13 Object-Relational Mapping (ORM): E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
This application is the back end for an e-commerce site, configured with a working Express.js API and using Sequalize to interact with a MySQL database. This application has not been deployed to GitHub or Heroku, so please find its functionality in the walk-through demonstration found in Section 4: Installation. 

## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [Usage](#usage)
4. [Installation](#installation)
5. [License](#license)
6. [Technologies Employed](#technologies-employed)
7. [Future Development](#future-development)
8. [Contributing](#contributing)
9. [Tests](#tests)
10. [Questions](#questions)

## Usage
### User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
### Acceptance Criteria 

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation
To run this locally:

1. Pull down and branch this repository
2. Run ```npm i``` to install all dependencies
3. Seed the database by running ```node seeds/```
4. Run the server with ```node server.js``` or ```npm run start```
5. Open any API testing tool like Postman or Insomnia to manipulate


The following animation shows the application's functionality from start to finish, including how to connect to mySQL database, entering schema and seeding. It also demonstrates invoking the application and testing all categories, product, and tag routes (GET, POST, DEL, PUT) in Insomnia:



https://user-images.githubusercontent.com/107900180/197929115-a090dac4-7b21-4632-999a-b66eb9d51a3c.mp4



## License 
This project is licensed under the MIT license.

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.<p/>For more information visit [MIT Licensing](https://choosealicense.com/licenses/mit/).

## Technologies Employed<br>
- JavaScript
- Node.js
- Express.js
- Sequalize
- MySQL
- Dotenv
- Object-Relational Mapping (ORM)

## Future Development
* Seamless deleting (cascading on delete)

## Contributing
We are not currently accepting contributions to this project.

## Tests
None

## Questions
Find us on GitHub: <br/>
[Creator: Insha Sayani](https://github.com/isayani)<br>
[ORM E-Comm Backend](https://github.com/isayani/orm-ecomm-backend)

---
?? 2022 Insha Sayani, Confidential and Proprietary. All Rights Reserved.
