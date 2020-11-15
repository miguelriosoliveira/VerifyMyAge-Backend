# VerifyMyAge Backend

Server made using [**TypeScript**](https://www.typescriptlang.org/), [**Node.js**](https://nodejs.org/), [**Express**](https://expressjs.com/), [**MongoDB Atlas**](https://www.mongodb.com/cloud/atlas) and [**mongoose**](https://mongoosejs.com/).

## Main responsabilities

This REST API provides the main functions for a CRUD of Users (name, age, email, password and address):<br/>
├── List of all users<br/>
├── Display of a single user<br/>
├── Creation of an user<br/>
├── Update of an user<br/>
├── User can change his/her password (if he/she remembers his old password)<br/>
└── Deletes an user

## How to run locally

1. Create a `.env` file based on the `.env.sample`:

	```shell
	cp .env.sample .env
	```

1. Fill the `MONGO_URL` variable with the connection string of your existent MongoDB:

	```ini
	PORT=3333
	MONGO_URL=mongodb://username:password@myhost/db_name?<options>
	```

1. Install dependencies and run the server!
	```shell
	yarn
	yarn dev
	```
