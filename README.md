# NodeJS Authentication App
> A complete authentication app with login, logout, register, forget password, email verification(for added security), and access control. Can be used as starter for other Node.JS applications. using Node.js, Express, Passport, JWT, Mongoose, and more. 

>The app is built using Node.js and Express, providing a fast and efficient backend architecture that can easily scale with the growth of your application. MongoDB is used as the database management system, allowing for secure storage and retrieval of user data.

>To ensure that user passwords are encrypted and secure, the app uses Bcrypt technology. Bcrypt hashes user passwords with a random salt and a strong encryption algorithm, making it almost impossible for an attacker to decipher the original password.

>The app also uses JSON Web Tokens (JWT) for secure authentication and authorization. JWTs are generated for each user upon successful login, and are used to verify user identity on subsequent requests. This approach provides an added layer of security and ensures that only authorized users can access protected resources within the app.

>EJS is used as the templating language, providing an intuitive way to generate dynamic HTML views that display user data and account information. This allows users to easily view and manage their account details, such as their profile information, login credentials, and other relevant data.

>Overall, your Authentication App is a powerful and secure solution for managing user authentication and authorization in your web application. The use of industry-standard technologies ensures that your app is both reliable and secure, while the app's scalability and performance make it suitable for any size of application.

## Web App Link

#The Server is Running online at: https://graceful-yak-garment.cyclic.app

![Screenshot (4)](https://user-images.githubusercontent.com/49118089/90341145-b776a900-e01a-11ea-93c8-4f6864a141c1.png)

## Technologies Used
1.  NodeJS
2.  Express
3.  EJS
4.  MongoDB
5.  Mongoose
6.  PassportJS
7.  JWT
8.  Nodemailer


## Prerequisites
- Git
- NodeJS
- CLI

## Installation

##### Clone the latest Repository

`git clone https://github.com/itsraunak/Authentication.git`

##### Into the project directory

`cd nodejs-auth`

##### Installing NPM dependencies

`npm install`

##### Then simply start your app

`npm start`

#### The Server should now be running at http://localhost:3000/

## Folder Structure

nodejs-auth <br>
├── assets <br>
│ --- ├── secure-icon.png <br>
│ --- ├── cyber-security-icon.jpg <br>
│ --- └── css <br>
│ -------- └── bootstrap.min.css <br>
├── config <br>
│ --- ├── checkAuth.js <br>
│ --- ├── key.js <br>
│ --- └── passport.js <br>
├── config <br>
│ --- └──authController.js
├── models <br>
│ --- └── User.js <br>
├── node_modules <br>
├── routes <br>
│ --- ├── auth.js <br>
│ --- └── index.js <br>
├── views <br>
│ --- ├── dash.ejs <br>
│ --- ├── forgot.ejs <br>
│ --- ├── layout.ejs <br>
│ --- ├── login.ejs <br>
│ --- ├── messages.ejs <br>
│ --- ├── register.ejs <br>
│ --- ├── reset.ejs <br>
│ --- └── welcome.ejs <br>
├── .gitignore <br>
├── package.json <br>
├── package-lock.json <br>
├── README.md <br>
└── server.js <br>
"# Authentication" 
