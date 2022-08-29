# Battleships-Game
This is the traditional board game "Battleships" programmed in Python, in which the opponent is the computer.

# Game Rules
You are expected to determine the coordinates of 10 ships of 4 different kinds on a grid that is 10x10. The same process will be done by your opponent (computer). The ship types are as follows:
1. Battleship x 4 (Occupies 4 spaces)
2. Cruiser x 3 (Occupies 3 spaces)
3. Destroyer x 2 (Occupies 2 spaces)
4. Submarine x 1 (Occupies 1 space)

# How does Grid Paper Look Like?
 A  B  C  D  E  F  G  H  I  J 
 
 —  —  —  —  —  —  —  —  —  — 
 
 O  O  O  O  O  O  O  O  O  O |1
 
 O  O  O  O  O  O  O  O  O  O |2
 
 O  O  O  O  O  O  O  O  O  O |3
 
 O  O  O  O  O  O  O  O  O  O |4
 
 O  O  O  O  O  O  O  O  O  O |5
 
 O  O  O  O  O  O  O  O  O  O |6
 
 O  O  O  O  O  O  O  O  O  O |7
 
 O  O  O  O  O  O  O  O  O  O |8
 
 O  O  O  O  O  O  O  O  O  O |9
 
 O  O  O  O  O  O  O  O  O  O |0

# How to State the Coordinates
For 10 times you have to state the coordinates of your ships. You can determine whether if it's standing vertical or horizontal on the grid plane. Therefore, the first letter in your input should be either ***"v"*** (meaning vertical) or ***"h"*** (meaning horizontal). Then, you have to write a letter A-J (corresponding to the x-axis of the uppermost left of the ship on the grid shown above) and then, a number (representing the y-axis of the uppermost left of the ship) should be written.
Hence, a sample input for a battleship would be: ***vg2***, which would result in a grid like (X means that you placed a ship at that position):
A  B  C  D  E  F  G  H  I  J 

 —  —  —  —  —  —  —  —  —  — 
 
 O  O  O  O  O  O  O  O  O  O |1
 
 O  O  O  O  O  O  O  O  O  O |2
 
 O  O  O  O  O  O  O  O  O  O |3
 
 O  O  O  O  O  O  X  O  O  O |4
 
 O  O  O  O  O  O  X  O  O  O |5
 
 O  O  O  O  O  O  X  O  O  O |6
 
 O  O  O  O  O  O  X  O  O  O |7
 
 O  O  O  O  O  O  O  O  O  O |8
 
 O  O  O  O  O  O  O  O  O  O |9
 
 O  O  O  O  O  O  O  O  O  O |0
 
 Remember that the ships cannot intersect with each other or they cannot be positioned out of boundaries of the grid. Therefore, you will be warned in a case like this.
 
 # Shooting Each Other
Now comes the battle! You should enter a letter (A-J) and a number (1-10) to bomb your opponent's grid. If there is a corresponding ship of your opponent on the coordinate you guessed, their ship will sink, and you will win a point. The same process will be done by your opponent in each round and the game will continue until all the ships of either you or your opponent's are bombed.

***Good Luck Captain!***
