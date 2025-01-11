# codealpha_task2
How It Works:
Backtracking Algorithm:

The program finds an empty cell (a cell with value 0).
It tries all numbers from 1 to 9 in the empty cell.
It checks if placing a number is valid using the isSafe() function.
If a number fits, the program recursively attempts to solve the rest of the grid.
If no number fits, it backtracks and tries the next possibility.
isSafe Function:

Ensures the number doesn’t appear in the same row, column, or 3x3 subgrid.
Input Grid:

The grid is a 2D array with 0 for empty cells.
