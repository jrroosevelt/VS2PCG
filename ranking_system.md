# Team Buckeye Competitive Play Ranking System
## Overview
After seeing the rankings coming out of the Philippines and being a part of other games that use a ranking system, Team Buckeye decided to start one for U.S.-organized VS 2PCG events.
  
We will try get other tournament/league organizers on board, to expand then rankings system. 

## How it works
Everyone starts with 1000 points. Every ranked match results in the winner taking points from the loser (assuming both players are participating in the ranking system). The amount of points depends on the difference in points between the players. 

If the winner has more points, the amount will be smaller. If the winner has fewer, points the amount will be bigger. 

This is determined by a formula (see below). The exchange of points will typically be a zero sum, meaning no new points will result in the exchange. Generally, points will only be added if: A.) A new player joins the ranking system or, B.) if a ranked player plays someone who isn't opted into the ranking system. 

## The gory details (ranking formula)
For anybody interested in the formula it is listed here. It's not as complicated as it looks, and is used by several organizations. 
Rn = R1 + 32(O - (10 \^ (R1/400))/(10 \^ (R1/400) + 10 \^ (R2/400))) 

- Rn is your new ranking 
- R1 is your current ranking 
- R2 is your opponent's ranking 
- O is outcome of match. (1 for a win 0 for a lose. .5 for a tie.)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MDI1MDY0MjIsLTU5OTA3NDY5MCwxMj
QzNTYxMzQwXX0=
-->