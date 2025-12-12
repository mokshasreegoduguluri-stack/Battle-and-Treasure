# Battle-and-Treasure
A simple C-based terminal dungeon game in which you explore a 15×20 grid, collecting healing items, fighting enemies with turn-based combat, and reach treasure to win. It also features random map generation, emoji-enhanced ASCII graphics, multiple weapons, and a fun treasure reward system.
C Concepts Used

Arrays: The game grid is represented by a 2D array (field[H][W]).

Functions: Isolate drawing, fighting, and treasure into separate functions.

Control structures including loops, switch-case, if/else statements are used for gameplay logic.

Directives: player HP is passed by pointer so it gets modified inside fight()

Randomization: using of rand() and srand() in enemy stats and items effect.

Character & string handling: Input for movement, map symbols.

✔ Why Make This Code

To practice core C programming concepts through a fun project.

To implement a simple interaction-based game on a grid.

learn how to handle user input, random events, and combat mechanics.

To get a feel for basic game loops and terminal graphics with ASCII/emoji.

✔ Aim of the Code

The goal is to traverse the player across the grid by surviving battles with enemies, gathering healing items, and reaching the treasure.

The player wins if he has killed all the enemies and reached to the treasure at the bottom right.

✔ How to Compile

Open the terminal and execute:

gcc battle and treasure.c -o battel and treasure


Then execute it:

./battel and treasure


(On Windows MinGW)

gcc battel and treasure.c -o battel and treasure.exe

battel and treasure.exe

✔ Important Notes

Emoji output may appear differently depending on your terminal.

Movement takes several characters as input at once: "wwasd"

HP capped at 100 upon healing.

Random elements in the game mean that each run is unique: different enemy positions, items, and damage. Player dies if he reaches zero HPs in combat.
