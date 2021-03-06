# Second Round Interview Test Project

# CREATE A NEW BRANCH. WHEN YOU ARE FINISHED SUBMIT A PULL REQUEST.

## Why another test project?
If you've made it this far, then you've passed the first coding test, which showed that you are familiar with AngularJS. Now, we need to make sure that you can work in the environment that our product is built in.

## Task
Build the front end to the application in this repo. Requirements are below, and design is unimportant, just use Bootstrap defaults. Function is everything in this test. If you are unfamiliar with JWTs, take some time and review middleware/auth.js.

## Requirements
- Use angular, ui.router, and ui.Bootstrap. Anything else you want to use is up to you, however your choices will be scrutinized.
- Front end stateless user authentication using JWTs.
- Separate pages for authenticated and non-authenticated users.
- Ability to post comments on the authenticated page. Just list all comments and have a text field that posts comments.

## Hints
- Use `npm start` to start the express application. It will be bound to port 8080 by default.
- If the application does not start, `npm install` might have been the first thing I would have done for a node application...
- If you're using Windows, why are you using windows? You're gonna have it rough with bcrypt.
- Authentication can be tested by sending a POST request to http://[SOME_HOST_PROBABLY_LOCALHOST]:8080/api/v1/authenticate
- You will be sharing the database with all other candidates. This means you might see comments you didn't create. User authentication for mongodb is disabled, and host information is hardcoded in config/config.js.
- Your front end code goes in '/public'.

## Bugs
- What bugs?