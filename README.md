# Rock Paper Scissors Game

Welcome to the classic Rock Paper Scissors game! This project is a simple web-based game where you can play against the computer. The game keeps track of your wins, losses, and ties.

## How to Play

1. Click on one of the move buttons: Rock, Paper, or Scissors.
2. The computer will randomly choose its move.
3. The result of the round will be displayed.
4. Your score will be updated accordingly.

## Technologies Used

- HTML
- CSS
- JavaScript

## Features

- Play Rock Paper Scissors against the computer.
- See the result of each round.
- Keep track of your wins, losses, and ties.
- Reset the score to start fresh.

## Screenshots

![Game Screenshot](/screenshots/rcs_1.png)

![Game Screenshot](/screenshots/rcs_2.png)


## Installation

1. Clone the repository:

```bash
   git clone https://github.com/nigmatovdev/rock-paper-scissors.git
   cd rock-paper-scissors
```
2. Open the index.html file in your web browser.


## How the Game Works
- You choose one of the moves: Rock, Paper, or Scissors.
- The computer randomly selects its move.
- The result of the round is displayed: Win, Lose, or Tie.
- Your score is updated based on the result.

## Game Logic
The game logic is implemented in the main.js file. Here's a brief overview:

- The playGame(playerMove) function is called when a move button is clicked.
- The computer's move is randomly selected using the pickComputerMove() function.
- The result of the round is determined based on the player's move and the computer's move.
- The score is updated accordingly.
- The updateScoreElement() function updates the score displayed on the screen.







