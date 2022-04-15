# OOP-Project-Scrabble
Contribute here to help with the Scrabble project for the OOP Lab

## Short Description

This game is designed to be played by 2 or 4 players. At the start of the game you will be asked to input the number of players, as well as name each of the players.

You should now see the game board, which is a matrix of 15x15 tiles. The round number, current player's turn and the current player's rack of letters (each player's rack is made up of 7 tiles) will be displayed. 

You can use the letters in the rack to create words. Each player has 100 extra letters, which will replenish each player's rack of tiles as they are used. The first turn must always have at least a letter in the center tile. 

Before inputting a word, the player is asked whether they would like their word to go down or right, and his word will be checked in the official scrabble dictionary API: https://www.programmableweb.com/api/word-game-dictionary-rest-api-v10.

After each turn, the user's total score will be updated, and the state of the board will be send to the next player.

After turn 1, each word played must have letters that end up in one of the existing words on the table

Each player can skip their turn up to 6 times, after which the 7th skip will result in an automatic resignation.

When the game ends, the scores of the players will be compared, and the player with most points will win

## How To Contribute

### PLEASE DON'T COMMIT DIRECTLY TO THE MASTER BRANCH!!!

0. Have a github account, and a tool of your choice for using git (I am using Git Bash). Some IDEs have integrated Git support (which is easy to use). You can also use Git with an interface if it's easier for you

1. Clone this repo: `git clone (url from Code button)`

2. Create a branch for your features: `git checkout -b (descriptive-branch-name-with-no-spaces)`

3. Try to only make changes to relevant files (i.e. if you work with the database, try not to modify the entire structure of the project, or make changes in the algorithms as this will create conflicts with branches of other people) 

4. For transparency, open a draft PR whenever you have some work ready to show: Go to Pull requests tab on Github, New Pull Request, Select `base` as `master`, and `compare` as your branch name: `descriptive-branch-name-with-no-spaces`

5. Wait for people to a) request changes to your branch, or b) approve your pull request

6. If there are no requested changes to your code, you can merge your pull request

### Always try to keep the `master` branch functional and free of bugs!
