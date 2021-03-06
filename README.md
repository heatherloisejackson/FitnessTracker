# FitnessTracker
An Javascript and MongoDB application that allows users to track their specific workouts.

## Description
This application, called StayFit, is a site that allows users to track their workouts in order to improve progress and accountability. Any user can access the site, log workouts in a workout plan, and view their stats. The stat charts shown on the user's dashboard page are generated by accumilating the total duration/weight of the day's workout (which can come from multiple workouts in the plan) and logging it compared to the most recent 7 workout plans. Building this application required experience with Javascript and Express and an understanding of how to use MongoDB and Mongoose. MongoDB generates the database with a Mongoose schema while Express handles the routes. In order to run this application on Heroku, MongoDB Atlas was required to access the database while on a live server.

## Installation
This application does not require any installation and can be accessed here: [StayFit](https://heathersfitnesstracker.herokuapp.com/?id=60ee2098fa027f0015fc91fe)

If you would like to install the application locally, clone this application onto your machine through GitHub, then open it in the command line and run the command "npm install" to make sure all the features are installed for the application locally. Update the seeds files with your own data. Run the command "npm run seed" and set up your local MongoDB as it pertains to the app. Next, run the command "node server.js" to begin using it on your browser.

## Usage
Below are screenshots of the working application.
![screenshot1](https://github.com/heatherloisejackson/FitnessTracker/blob/main/public/images/Screen%20Shot%202021-07-13%20at%206.22.21%20PM.png)
![screenshot2](https://github.com/heatherloisejackson/FitnessTracker/blob/main/public/images/Screen%20Shot%202021-07-13%20at%206.22.51%20PM.png)
![screenshot3](https://github.com/heatherloisejackson/FitnessTracker/blob/main/public/images/Screen%20Shot%202021-07-13%20at%206.22.37%20PM.png)

## Credits
Thank you to Penn LPS Coding Bootcamp, instructors, peers, [JavaScript](https://www.javascript.com/), [Node.JS](https://nodejs.org/en/), [NPM](https://www.npmjs.com/) and its packages, [Express.js](https://expressjs.com/), [MongoDB](https://www.mongodb.com/), [Mongoose](https://mongoosejs.com/), [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) & [Robo3T](https://robomongo.org/), and Heroku.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## How to Contribute
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](code_of_conduct.md)

Contact me @heatherloisejackson on GitHub
