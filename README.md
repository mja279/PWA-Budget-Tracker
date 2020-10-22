# Unit 18 PWA Homework: Online/Offline Budget Trackers

<img src="./assets/images/budget-tracker.gif">

This Budget Tracker application allows users to keep track while online and offline. The user is able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, the app will populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Dependencies

To run the application from your computer, you will need to install the following dependencies: 
  > express
  
  > mongoose

  > logger

  > compression

Metrics from the deployed website are stored via Mongod DB Atlas' AWS environment. 
