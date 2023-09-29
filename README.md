# Sociopedia Social Media App

Sociopedia is a social media application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to connect, share posts, and interact with each other in a social media environment.

## Screenshots
### Login Page :-

![Screenshot (14)](https://github.com/rohitdhakane6/Social-Media-App-Sociopedia/assets/109848812/c42c49c9-bd11-4848-b60c-517fac5797c3)

### Registration Page :-
![Screenshot (15)](https://github.com/rohitdhakane6/Social-Media-App-Sociopedia/assets/109848812/4b253de0-5231-4265-bb75-f47971af2b32)

### Post & Account :-
![Screenshot (16)](https://github.com/rohitdhakane6/Social-Media-App-Sociopedia/assets/109848812/9c3625e9-c4e9-4269-94e3-f06bd8375efe)

## Installation

To run the Sociopedia Social Media App locally on your machine, follow these steps:

### Prerequisites

Before you begin, make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 12 or higher)
- [MongoDB](https://www.mongodb.com/)

### Clone the Repository

```
git clone https://github.com/rohitdhakane6/Social-Media-App-Sociopedia.git
```

## Install Dependencies

Install server dependencies
```
cd server
npm install
```

Install client dependencies
```
cd client
npm install
```
## Set Up Environment Variables

Create a .env file in the server directory with the following content:
```
# MongoDB connection URI
MONGODB_URI=your_mongodb_connection_uri

# JWT secret key for authentication
JWT_SECRET=your_jwt_secret

# Port for the server to run on
PORT=3001
```

Replace your_mongodb_connection_uri with your actual MongoDB connection URI and your_jwt_secret with your desired JWT secret key for authentication.

## Start the Development Server
```
# Start the server (from the server directory)
cd ../server
npm start

# Start the client (from the client directory)
cd ../client
npm start
```
The Sociopedia Social Media App should now be running locally on your machine. You can access it by opening your browser and navigating to http://localhost:3000.
