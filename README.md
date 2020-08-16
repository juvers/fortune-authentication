### Fortune Authentication
#### A React.js with Express Authentication and Authorization
--

### Description
##### Client side created with React, React Router and Axios. Utilize bootstrap for layout and styling and ensure form validation.
##### Server side employed Node.js Express. Secured authentication with jsonwebtoken(JWT) was utilized. Sequelize for interacting with MySQL db.

###  Technology
- React
- Axios
- Express
- bcryptjs
- jsonwebtoken
- Sequelize
- MySQL

### Directory Structure
#### Client
#### Server
- config: configure MySQL db, Sequelize and Auth Key
- routes: post routes for signup and signin with public and protected routes
- middlewares: verifysignup.js to check duplicate username or email and authJwt.js to verify token and userrole in db
- controllers: 