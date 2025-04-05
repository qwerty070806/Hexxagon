## Hexxagon
This repository contains the implementation of a strategic board game
called Hexxagon using Python and the pygame library. The game supports
multiple modes, including Human vs Human, AI vs AI, and Human vs AI, with
AI strategies implemented using Minimax and Alpha-Beta pruning algorithms.
The objective is to provide an engaging gameplay experience while
showcasing the implementation of advanced AI techniques.
## Objectives
1. Create a visually appealing hexagonal grid-based board game.
2. Implement various player types:
• Human players.
• AI players using Minimax and Alpha-Beta pruning.
• Random move generators.
3. Provide multiple gameplay modes:
• Human vs Human.
• Human vs AI (minimax).
• Human vs AI (alpha-beta).
• Human vs Random
• AI (minimax) vs AI (minimax).
• AI (minimax) vs AI (alpha-beta).
• AI (minimax) vs Random.
• AI (alpha-beta) vs AI (alpha-beta).
• AI (alpha-beta) vs Random.
• Random vs Random.
4. Ensure smooth interaction and user-friendly UI.

# Installation
Prerequisites
Python 3.10 or higher

Pygame library

Follow these steps:

```sh

# Install the necessary dependencies.
pip install pygame

```
How to Play
Game Setup
1.Select player types for Player 1 and Player 2 using dropdown menus:

2.Options: Human, AI-minimax, AI-alpha-beta, Random.(for each player)

![mainmenu](https://github.com/user-attachments/assets/bd41f0e2-300c-497c-b1ac-05c1eee7deb5)


Click on the "Start Game" button to begin.

![startgame](https://github.com/user-attachments/assets/0837614f-be4e-49b3-9574-e90a44bafa88)

# Rules
1.Players take turns placing or moving their pieces on the hexagonal grid.

2.Pieces can either clone to adjacent cells or jump to adjacent of adjacent cells.

3.Opponent's pieces adjacent to the moved piece are converted to the current player's color.

4.The game ends when no valid moves are possible or the grid is full.

# Winning Criteria
1.The player with the most pieces on the board at the end of the game wins.
