# comeon-javascript-test

Simple applicant's test for Javascript coders.

## Assignment Overview

The assignment is to use Javascript and jQuery to tie together existing HTML and data to create a minimal, working casino website.

Basic HTML, CSS, images and JSON data is provided, however, feel free to impress by changing and enhancing any of these parts for an even better experience!

Your mission is to provide the Javascript code that makes the parts work as described, below.
The data is provided via jQuery’s [$.ajax()](http://api.jquery.com/jquery.ajax/) call, and feel free to use any other openly available library for
validation, templating, dependency injection, etc.

## Assignment criteria

We want to see how you approach and solve a problem, as well as look at code style and quality. Do take your time to do it right, rather than fast.
Extra effort to improve on the "website" will be noted. :)

While the test is primarily focused on Javascript, by all means use or change the HTML or CSS when that makes sense.

Be prepared to discuss your choices and code when delivered.

These parts needs all to be completed for the assignment to be complete:

### Login functionality

* Connect the login form to the /login ajax call.
* On valid username/password, transition to the games list screen.
* On invalid username/password, provide feedback and allow to try again.

### Games list screen

* List all games from the /games ajax call.
* Provide functionality for filtering by typing.
* Make it possible to start a game by clicking on the name or icon.

### Game play screen

* Load the selected game via the provided API
* Provide a way to go back to the Games list screen

## API
TODO

Defined in mock/mock-api.js

/login

/games

/categories

## Loading a game

We have written an API for loading the game. Here's a simple example on how to load a game through our API:

```javascript
comeon.game.launch('starburst');
```

It basically takes a game code as an in parameter.
The div with id game-launch will be replaced with an object tag that loads the game.

