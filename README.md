# eCommerce

# Table-of-Contents
  * [Walk through Video](#walk-through-Video)
  * [Git Repo](#git-repo)
  * [Dependency](#dependency)
    * [System](#system) 
    * [On project](#on-project) 
    * [Artifact](#artifact) 
  * [User Story](#user-story)
  * [Acceptance Criteria](#acceptance-criteria)
  * [Application Invoked](#application-invoked)
  * [Database schema](#database-schema)
    * [Table Describe](#table-describe)

# [Walk through Video](#table-of-contents)


# [Git Repo](#table-of-contents)
```
https://github.com/kabirfaisal1/eCommerce.git

```
# [Dependency](#table-of-contents)
  ## [System](#table-of-contents)
  ```
      node.js
  ```
  ## [On project](#table-of-contents)
  ```
  npm init
```
  npm install mysql2
```
```
  npm install sequelize
```
  npm install dotenv

  ```
  ## [Artifact](#table-of-contents)
  * create .env file and enter following code
  ```
  DB_NAME='ecommerce_db'
  DB_USER='root'
  DB_PASSWORD='password'
  ```

# [User Story](#table-of-contents)
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

```
# [Acceptance Criteria](#table-of-contents)
```
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
## [Application Invoked](#table-of-contents)
`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`



## Node and NPM Doc
https://nodejs.org/en/download/package-manager/
https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
