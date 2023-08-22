# E-Commerce Back End

## Project Description 

This project involved building the back end for an e-commerce site by configuring a working Express.js API to use Sequelize to interact witha MySQL database.

# Installation

1. Pull down and/or branch this repository
2. Run npm i to install all dependencies
3. Install `MySQL2 Package` with `npm i mysql2`
4. You will also need Insomnia/Postman installed on your device.

# Usage

1. Initiate the database with `mysql -u root -p`
2. Then `source db/schema.sql` to create the tables. 
3. Exit the mysql terminal with `quit`. 
4. Run `node seeds/index.js` to seed the data.
5. Run `npm run start` to start the server.
6. Use Insomnia for the GET,POST, PUT & DELETE requests.


## Acceptance Criteria

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



# Application Preview

[Click here to access the application recording.](https://drive.google.com/file/d/1OkFLk5XztsY39nATpf0TOzmup0LElTdI/view?usp=sharing)

# Links

[Click here to access the files on the github repository.](https://github.com/fadumaabdi/ecommerce)

