# :heavy_dollar_sign: Unit 18 PWA Homework: Online/Offline Budget Trackers  :money_with_wings:

## Business Context
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Concept
Add functionality to our existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

  * When brought back online:

  * Offline entries should be added to tracker.

## Instructions
  * Open a terminal and run `npm install` to create the node_modules folder.*  
  * Run `node server.js`, this will connect you to PORT 3000 and local database.  Open a browser and
    type `http://localhost:3000/` or `localhost:3000` and hit enter and this will display the Budget Application.
  * Once the App opens, in the right hand side of the command line, click on the "+" enclosed in a circle
    to install the app.
  * Budget Setting:
    * You can set a Total monthly Budget and then subtract from it the expenses that you spend or 
    * you can just add the expenses that you incur that month and the Graph will show you how much you
      are spending 
  * Working Offline:
    * After entering some budget items, Inspect the Web page by right clicking on it and choosing
      `Inspect`.   Click on `Application` and select `Service Workers`.  Check the Offline box and refresh the screen.  All the data disappears as the application is Offline.  Enter a new item, uncheck the Offline box and then click refresh.   The information that was there before should return and the item added also.  You might need to refresh a few times.

## User Story
```
  AS AN avid traveller
  I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
  SO THAT my account balance is accurate when I am traveling
```
## Acceptance Criteria
```md
  GIVEN a user is on Budget App without an internet connection
  WHEN the user inputs a withdrawal or deposit
  THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```
## Tools:
 * Node
 * Express
 * Mongoose schema * 
 * Models
 * Javascript        
 * Package json 
 * CSS
 * HTML
 * Heroku

## Links:
  * Github Repository:
    [Github](https://github.com/whintzen/Online-Offline-Budget-Trackers)

  * Heroku Repository: 
    [Heroku](https://docs.google.com/document/d/1lyepxmd7pjRYFfgmMBWRrXZsqlJJJnfZ6mc0PrZIrRQ/edit?usp=sharing)
  
  * Budget Tracker App Images
     ![Image of Deduction from a monthly Budget](https://github.com/whintzen/Online-Offline-Budget-Trackers/blob/master/public/icons/Setting-Budget.jpg)

     ![Image of Summing up spending](https://github.com/whintzen/Online-Offline-Budget-Trackers/blob/master/public/icons/Totalling-Budget.jpg)
  
  