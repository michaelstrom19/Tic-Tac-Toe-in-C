# Tic-Tac-Toe in C
This Repository contains a simple game of Tic-Tac-Toe implemented in C with colorful text. The game takes input from the command line, and users can take turns placing X or O, along with the ability to save and exit the game to return at a later time.

## Features
* command-line interface
* Ability to save and resume game progress
* prevents invalid inputs
* Detects the winner and displays the game result
* Rainbow text :)

## Functions
* displayBoard(): Prints the current state of the game board
* legalMove(): Checks if the chosen move is valid. If valid, updates the board and switches the active player. Otherwise, prompts the player to try again.
* gameWon(): Checks all possible winning conditions. Returns 1 if a player wins, 0 for a draw, and -1 if the game is still ongoing.
* readGame(): Loads a saved game from TicTacToeSave.txt and reads current board state.
* writeGame(): Creates or resets a save file to start a new game.
* saveGame(): Saves the current game state, including the board and active player, to TicTacToeSave.txt.
* printline(): Helper functions that prints a colored separator line to visually divide the board.
* Color Functions (): Apply specific colors to text output for better visualization.

## Screenshots
![](https://github.com/michaelstrom19/Tic-Tac-Toe-in-C/blob/main/image1.png)
![](https://github.com/michaelstrom19/Tic-Tac-Toe-in-C/blob/main/image2.png)

