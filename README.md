<h1 align="center">
🌐 Ecommerce-SpenseChallengeSubmission
</h1>
<p align="center">
MongoDB, Expressjs, React/Redux, Nodejs
</p>


> Eshop is a fullstack implementation in MongoDB, Expressjs, React/Redux, Nodejs.

Eshop has all the functionality which includes:
> Login Page,
> Super Admin Dashboard,
> Vendor Dashboard,
> Customer Functionality,
> Payment Gateway,
> Discount Campaigns,
> Data Tracking & Analytics,
> Search functionality,
> Feature that displays popular products



# Usage (run fullstack app on your machine)

## Prerequisites
- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^18.16.0
- [npm](https://nodejs.org/en/download/package-manager/)


## Client-side usage(PORT: 3000)
```terminal
$ cd frontend          // go to frontend folder
$ yarn     // npm install packages
$ npm start        // run it locally

// deployment for frontend app
$ npm run build // this will compile the react code using webpack and generate a folder called docs in the root level
$ npm run start // this will run the files in docs, this behavior is exactly the same how gh-pages will run your static site
```

## Server-side usage(PORT: 8000)

### Prepare your secret

run the script at the first level:

(You need to add a JWT_SECRET in .env to connect to MongoDB)

```terminal
// in the root level
$ cd backend
$ echo "JWT_SECRET=YOUR_JWT_SECRET" >> src/.env
```

## Socket usage(PORT: 4000)


### Start

```terminal
$ cd backend   // go to server folder
$ npm i       // npm install packages
$ npm run dev // run it locally
$ npm run build // this will build the server code to es6 js codes and generate a dist file
```

## Deploy Server to [Render](https://ecommerce-spensechallengesubmission.onrender.com)


# Screenshots of this project

