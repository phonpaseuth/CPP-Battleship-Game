# CPP-Battleship-Game
Programming and Problem Solving with C++ 5th Edition

Nell Dale and Chip Weems

Programming Problem 11-1 PG.

Write a program to play a game in which you try to sink a fleet of five navy vessels by guessing their locations on a grid. The program uses a random numbers to position its ships on a 15x15 grid. The ships are of different lengths as follows:

Frigate: 2 locations, Tender: 2, Destroyer: 3, Cruiser: 3, Carrier: 4.

The program must pick one square as the starting location, then pick the direction of the ship on the board, and mark off the number of squares in that direction to represent the size of the ship. It must not allow a ship to overlap with another ship or to run off the board.

The user enters coordinates in the range of 1 through 15 for the rows and A through O forth ecolumns. THe program checks this location, and reports wheather it is a hit or a miss. If it is a hit, the program also checks wheather the ship has been hit in every location that it occupies. If so, the ship is reported as sunk, and the program identifies which ship it is.

The user gets 60 shots to attempt to sink the fleet. If the user sinks all of the ships before using all 60 shots, then he or she wins the game. At the end of the game, the program should output the grid so that the user can see where the ship are located.
