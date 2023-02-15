# E-Commerce Backend

A back-end application for an e-commerce site that was built using Express.js API and configured to use Sequelize to interact with a MySQL database.

This application does not have a front end so all the functionality has been demonstrated with walkthrough videos.

---

## **Table of contents**

  - [Installation](#installation)
  - [Usage](#usage)
  - [Technologies Used](#built-with)
  - [Demo Video](#demonstration-video)
  - [License](#license)
---
## **Installation**

Clone this repo on your local machine:

```sh
$ git clone https://github.com/asish-dewan/ecom-backend
```

To install and set up the application, run:
```sh
$ npm i
$ npm install mysql2
$ npm install sequelize
```

Create a .env file in the root directory of the project, in order to connect to your MySQL database. Here's an example:

file: .env
```
DB_NAME=ecommerce_db
DB_USER=root
DB_PW= (set your password here)
```

---

## **Usage**

To finish the set-up the application, you will need to seed the database:
  
1. Connect SQL server

```
$ mysql -u root -p
```
2. Once SQL is running, select the database from the schema.sql file

```
mysql> source db/schema.sql

mysql> use (database name from .env file)

mysql> quit
```
3. Run the seed

```
npm run seed
```

4. Start the server

```
npm run start
```

---

## **Technologies Used**
* [**Node.js**](https://nodejs.org/en/about/)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [Express.js](https://www.npmjs.com/package/express)
* [mysql2.js](https://www.npmjs.com/package/mysql2)

---

## **Demonstration Video**
Walkthrough video to demonstrate the functionality of the back end: [Demo Video on Google Drive](https://drive.google.com/drive/folders/19FHUuMpGa5BxBrRR9-Jms-C7yCyd0AEd?usp=share_link)



## **License**
This application is licensed under the MIT License.

---