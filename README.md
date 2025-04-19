# Minesweeper
*Last updated on 12/22/2023.*

This repository is about my Python game, Minesweeper.

## Instructions
In Minesweeper, there is a grid (or minefield) containing cells, some of which are mines. Your goal is to reveal all the cells that are NOT mines without uncovering one.

There are five types of cells in this version:
  - Unopened cells (?), which represent cells that have not been revealed.
  - Numbered cells (1-8), which represent how many mines are in the 8 cells around them.
  - Blank cells (□), which represent there are no mines left in the 8 cells around them.
  - Flagged cells (⚑), which the player adds to represent a potential mine.
  - Mines (M), which represent cells the player must not reveal in order to win the game.

To reveal (or flag) a cell, you will need a column and row number. Look at the top and left of the grid to find them, respectively.

## Blog Post (for Codecademy)
I like Minesweeper and coding, so I decided to make my version in Python. My version and the others aren't very different, apart from the player having to input the column and row numbers due to the limitations of base Python.

![image](https://github.com/jmariz0/Minesweeper/assets/153701757/588adc26-a198-4acf-b778-5b7d2de5c957)

*Image showing a 10 by 10 grid with unopened, blank, numbered, and flagged cells*

In terms of code, Minesweeper was easy to make. My code contains a "Cell" class, and functions that deal with
- Making an empty grid
- Adding mines to the grid
- Adding numbered cells around mines
- Revealing cells from "?" to their actual status
- Displaying the grid in the console

I also added other lines of code to make the game as a whole look nicer. *Link to full code is [here](https://github.com/jmariz0/Minesweeper/blob/main/Minesweeper).*

In conclusion, making Minesweeper was a fun and rewarding experience. I hope to produce more games and programs in the future.
