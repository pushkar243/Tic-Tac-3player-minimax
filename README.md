# Tic-Tac-3player-minimax
Description: This one is an interesting problem where we can play Tic-Tac-Toe with 3 players. 2 players are Computer and one is human. Implemented min-max algorithm
One of the extension would be to try something similar with 3 players Chess and with 3 sides ... Always wondered how it will work 
Problem statement 1: Gaming
 Code involves 3 players - User (X), Computer 1 (O), Computer 2 (T)
 It is assumed that Computer 1 and Computer 2 players are playing against user (X) but they 
are not playing against each other.
 Draw board function draws 6X6 board
 Endofgame function checks for column or row or diagonal win
 Alpha Beta (max and min) functions are created to check alpha – beta values for each 
position
 Static Evaluation is considered as below: -
o If User (X) wins – Static Evaluation is -1
o If User (O or T) wins – Static Evaluation is +1
o If User (no one) wins – Static Evaluation is 0
![image](https://github.com/pushkar243/Tic-Tac-3player-minimax/assets/8349513/52cd41cf-4204-44cf-a853-72cfe8875a1a)
