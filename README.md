# RubugsSolver
I am planning on using a game tree approach. Although zyada idea nahi hai kaise use karte hain but basics pata hain and feel like use kar sakte hain.
So, tree mein we'll have to find the shortest possible path from starting node(scrambled state) to the solved state, and also we have to make this space efficient

A Random Start and a fixed end!

## Search guided solutions

### 1) Informed $A^*$ Search 
Heuritics :

a) At any state, take the max over pieces of moves required to move a piece into the correct loaction

### 2) RL-based

Train a Deep neural network to predict the best move and value based on the current state. Use a tree search to get the best solutions
