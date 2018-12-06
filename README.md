# 50002 Bish Bash
SUTD ISTD 50.002: Bish Bash

A game built using the Mojo as part of SUTD's 50.002 Computational Structures module.

In this game, two players are presented with 3 sets of 9 LED lights each. There are three different modes that both players can choose from before starting the game:

1. The default mode is where players have to choose the corresponding set of LED lights with the HIGHEST number of LEDs being lit up. (0000 on the display)
2. The second mode is where players will have to choose the corresponding set of LED lights with the SMALLEST number of LEDs being lit up. (1111 on the display)
3. The third mode is where players will have to choose the corresponding set of LED lights with the MIDDLE number of LEDs being lit up. (2222 on the display)

There are 5 rounds in total. In each round, the player who chooses the correct option will be awarded with one point. The player who chooses the wrong option however, will have one point deducted, and the other player will also be awarded an additional point (DOUBLE JEOPARDY).

The player with the most number of points wins!

# Technicalities
3 ALU functions used: CMPEQ, ADD, SUB

ALU: 16-bit

# References
Some of our modules were referenced from the Alchitry website (https://alchitry.com/blogs/tutorials/) - without which we would have spent even more time trying to decipher the workings of the Mojo!
