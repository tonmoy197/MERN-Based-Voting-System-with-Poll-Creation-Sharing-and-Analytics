# Vote App

A full-stack Voting App built using the MERN stack, inspired by freeCodeCamp's project. It allows users to create, manage, share, and vote on polls. Both authenticated and unauthenticated users can participate, view results in real-time charts, and even suggest new options for polls. Write name for this project

## User Stories

* As an authenticated user, I can keep my polls and come back later to access them.
* As an authenticated user, I can share my polls with my friends.
* As an authenticated user, I can see the aggregate results of my polls.
* As an authenticated user, I can delete polls that I decide I don't want anymore.
* As an authenticated user, I can create a poll with any number of possible items.
* As an unauthenticated or authenticated user, I can see and vote on everyone's polls.
* As an unauthenticated or authenticated user, I can see the results of polls in chart form. (This could be implemented using Chart.js or Google Charts.)
* As an authenticated user, if I don't like the options on a poll, I can create a newoption.

## Getting Started

Include a `.env` file in the `server` directory with the following environment variables.

```
PORT = 4000
DATABASE = 'mongodb://localhost/<DATABASE_NAME>'
SECRET = 'ThisIsATemporarySecretKey'
```

## Built with

* nodejs
* express
* mongodb
* mongoose
* bcrypt
* jsonwebtoken
* react
