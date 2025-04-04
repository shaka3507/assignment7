## Battleship

## Live URL
https://shaka3507.github.io/assignment7/index.html

## Questions

1. Javascript object feels the most useful to use - the methods available to it feel the most accessible in terms of readibility. Associative array syntax and even JSON syntax seems to have more structure. For example JSON needs double quotes for strings, and JS objects can take single or double quotes. This makes sense since JSON is used as an intermediary between many languages (for APIs), so more structure and a standard is needed.
2. The least challenging part of this was utilizing classes to toggle whether a user has hit or missed a cell. Adding classes once during game play vs having to check for their existence or toggling them off or on feels easier to work with since someone cant change the state of a cell from miss to hit or vice versa.

Tasks
- [x] Create 6x6 grid for game board
- [x] When user clicks, on a square, respond with hit/miss or sunk depending on if they hit ship, missed it, or hit all pieces of it
- [x] Dont tell user which ship was sunk on hit
- [x] Color code plays - blank is unselected, red is hit and grey means miss
- [x] Give player up to 20 guesses to find all ships
- [x] On game over let user know locations of individual ships


