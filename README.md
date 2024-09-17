
# Auth App(Express)

## Overview
This is a simple backend project that implements user authentication features such as signup and login using **ExpressJS** and **MongoDB**.

## Features
- **User Signup**: Users can register with a username and password.
- **User Login**: Users can log in with their credentials.
- **JWT Authentication**: Uses JSON Web Tokens (JWT) for secure authentication and authorization.
- **Error Handling**: Centralized error handling for user-friendly error messages.
  
## Technologies Used
- **Node.js**: JavaScript runtime for server-side code.
- **Express.js**: Fast and lightweight web framework for Node.js.
- **MongoDB**: NoSQL database to store user information.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB.
- **JWT**: Used for secure authentication of users.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/rishika105/auth-app-express.git
```

2. Navigate to the project directory:

```bash
cd auth-app-express
```

3. Install dependencies:

```bash
npm install
```

4. Create a `.env` file for environment variables (such as MongoDB URI, JWT secret):

```
PORT = 4000
MONGODB_URL=<Your MongoDB connection string>
JWT_SECRET=<Your secret key>
```

5. Start the server:

```bash
npm start
```

The server will start running on [http://localhost:3000](http://localhost:3000).

## API Endpoints

- **POST** `/api/signup`: Register a new user.
- **POST** `/api/login`: Authenticate an existing user and return a JWT.
  
