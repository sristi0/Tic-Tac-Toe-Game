# Tic-Tac-Toe Game

We will develop a Tic-Tac-Toe game in C++. Tic-Tac-Toe is a game played between two players, usually with paper and pencil. In this project, we will create a C++ program that displays the game on the console screen and allows players to use different keys from the keyboard to play it.

## Rules of Tic-Tac-Toe

Following are the rules that define how to play the Tic-Tac-Toe game:

- A player can put only a single letter X or O in the 3x3 grid on each turn.
- Both players will take turns alternately until someone wins or the game ends in a draw.
- To win, a player must create a horizontal, vertical, or diagonal line consisting of three of the same letter.
- The game ends in a draw if all cells are filled with X or O letters but no line is formed.

## Features of Tic-Tac-Toe in C++

This game includes the following features:

- Developed on a 3×3 grid.
- Designed for two players.
- Each player can choose a letter between X and O.
- Players take turns alternately.

## Components of the Game

The game is composed of the following components, including functions and data structures to provide the basic operations:

1. **Game Board**

   To create a Tic-Tac-Toe board, a 3x3 array initialized with spaces is used:

   ```cpp
   char board[3][3] = {{' ', ' ', ' '}, {' ', ' ', ' '}, {' ', ' ', ' '}};
