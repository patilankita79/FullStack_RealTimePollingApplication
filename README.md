# FullStack_RealTimePollingApplication
This is a full stack real time polling application. In this application the user will see votes on the front-end as they come in, so user doesn't need to refresh the browser periodically. For front-end, Canvas JS is used to display the result in charts and for backend NodeJS and express are used. Pusher API is used for real time subscriptions. When a vote is submitted to the server through the form, Pusher will trigger the response and update the front-end i.e. result will displayed in charts.

<hr>

### Step by step Approach

- To use the Pusher API, you need to have account with Pusher. To create an account Sign up
- After login, we are redirected to Pusher dashboard. Go to **Your apps** and **create a new app**, fill in all the details which    includes choice of technology for front-end and back-end. After creating an app, you can see all the required instructions.


**1. Setting up the backend**
  - Generate the package.json with command => npm init
  - Install the following dependencies
    - express 
    - body-parser 
      - body-parser is needed to handle form-submission (We need to get the data)
    - pusher
    - cors
      - To let people from other domain make request without having issue
    - mongoose
  - Create app.js file with the command => touch app.js
  - Create a public folder and create index.html inside public folder
  - Create routes folder which will contain all the routes
    
  
  
<hr>

# References
https://pusher.com/
