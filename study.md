# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss on Monday morning.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
  - How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code moodular.
-   What creative spin will you add to your project.
-   How you will use version control to backup / track your project.
-   Do you plan to attempt any of the bonuses.


 1. https://moqups.com/#!/edit/philschoof/6Oo0ssCT


2,3,4. Each player will have an object that contains their username, chosen symbol, and a css class name property. Every cell on the game board will have a unique ID, and an 'availalbe' class that will be removed when its clicked so it cant be clicked twice. Javascript will have a currentPlayer variable set to player 1 and turn counter variable. When the first player clicks a cell, jQuery will add the players css class property and icon to that cell, and the currentPlayer variable will switch. When the turn counter reaches four, jQuery will start looping thrugh a nested array of possible winning game boards, and use an array method to see if any winning combinations have a user's css classes attached to all of the items.

5. As a user, I want to know what cell I'm going to place my x or o in.

  As a developer, I want to use pseudo-classes to animate the page to make the game more interactive

  As a user, I want to be able to customize my game peice.

  As a developer, I want to include a drop down menu of icon choices that willl update the user objects 'symbol' property.

  As a user, I want to be able to restart a game at any time.

  As a developer, I plan to have a new game button that when pushed will reset the game board


6. HTML, CSS, and initial javascript needed to display user information will all have separate files. There will also be separate files for the user objects, game logic, and sign-up/login/log out scripts.

7. I plan on having different icons for players to use in place of x's and o's, and maybe some css/jquery animation to show the current player and winner

8. I will most likley make separate branches for each section of the app, i.e. front-end, game logic, api calls, etc

9. I don't expect the project will go as smoothly as I'm hoping, so unless all the features I have sketched out now can be completed and tested with enough time left to get the bonuses completed and tested, I don't think I'm going to pursue the bonuses.
