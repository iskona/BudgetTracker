# BudgetTracker
Online/Offline Budget Tracker App

[Click here](https://safe-river-99178.herokuapp.com/) to launch this project on Heroku.

## Overview:
This app allows the user to enter an expense title and ammount and then indicate by button click if this is being added to the budget or subtracted from the budget. This data is stored in a database as well as being passed to a chart that keeps track of each debit or credit. This application is a PWA, or progressive web app as well meaning that it allows for the application to continue it's functionality while offline. It locally stores transactions while offline using indexedDB and passes those transactions back to the applications database once returning to online status, working with the service worker to do so.

## Built with:

* MongoDB
* Mongoose
* Node.js
* Express.js
* IndexedDB
* Service-Worker

## User Story:

As an avid traveller I want to be able to track my withdrawals and deposits with or without a data/internet connection so that my account balance is accurate when I am traveling.
