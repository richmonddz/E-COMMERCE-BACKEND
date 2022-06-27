# E-COMMERCE-BACKEND

## Description

A mysql database and application backend for an e-commerce site

### Table of contents

- [Demo](#Video-Demo)
- [Description](#Description)
- [Installation](#Installation)

## Installation

1. First fork the github repo https://github.com/richmonddz/E-COMMERCE-BACKEND
2. Clone your newly forked repo to a directory on your computer through your terminal

```
git clone https://github.com/richmonddz/E-COMMERCE-BACKEND.git
```

3. Install the node dependencies to the application by entering in the terminal:

```
npm i
```

```
npm install sequelize
npm install mysql2
npm install dotenv
npm install express
```

4. Before continuing navigate to the .env file and input your MySQL credentials

```
DB_USER='root'
DB_PW=''
DB_NAME='ecommerce_db'
```

5. Then login to your MySQL shell by using

```
mysql -u root -p
```

6. Once logged in create the schema from the MySQL shell

```
source db/schema.sql
```

7. Quit the Mysql shell and seed the database in the command line

```
npm run seed
```

8. After the you seed the database you can initate the server

```
npm start
```

## Video-Demo

https://user-images.githubusercontent.com/100399374/175886891-7ea5986a-485f-41e9-98e5-bf1b2d9d0d0a.mp4



**_Link to Demo Video_**
