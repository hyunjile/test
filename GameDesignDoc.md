# Game Design Document PA5

Milestone 5A 

----

## Requirements

### A. Things

**1. Wall with a hole**

The board will be divided by a wall with a hole in the middle.
The left side of the board will be written as 'O' and the right side will be 'X'.

The image of the wall with a hole is in the board/layout of the user interface section (section E).

**2. Two blockers**

They will be on each side of the wall, acting as blocking obstacles for the user to move to either side. They can only move vertically (up and down) near the hole in the wall. The user loses a life if he/she fails to avoid it/them. The blockers cannot be killed with bullets.

![alt text](http://octodex.github.com/images/Professortocat_v2.png "Layout")

**3. Hunter**

There will be a hunter that tracks the user. It can move however to follow the user. Once it reaches the user, the user loses a life. The hunter has two lives. It can only be killed when the user uses both bullets to kill it.

![alt text](http://octodex.github.com/images/Professortocat_v2.png "Layout")

**4. Guards**

There will be guards (number not determined) on each side of the board. They move randomly.

![alt text](http://octodex.github.com/images/Professortocat_v2.png "Layout")

**5. Two Helpers**

There are two helpers (one on each side). The user has to meet both helpers to get a help. When the user collides with both of them, the helper randomly pick an enemy (blocker, hunter, or guard) and kills it for the user. The enemies cannot kill them. The helpers move diagonally. 

![alt text](http://octodex.github.com/images/Professortocat_v2.png "Layout")

**User**

![alt text](img690.imageshack.us/img690/6356/userzg.png "User")


### B. How

This is a true/false question game.
When the game starts, the user will be located on the hole of the wall (the center).
There will a statement and a timer (20 seconds) on top.
The left side of the board is 'O' and the right is 'X'.
The user moves to 'O' if he/she thinks the statement is true.
The user moves to 'X' if he/she thinks the statement is false.

There will be two bullets given to the user in every question.
Thus, the user can only shoot bullets twice. 
Also, the bullets cannot kill the blockers.
Also, you need to shoot at the hunter twice to kill it.
      If you hit the hunter with a bullet once, the hunter does not die.
      Only when you hit it twice, it dies.

There are helpers that helps the user. The user has to meet both of them to get one random enemy killed without using a bullet.

The object of this game is to correctly answer the question while avoiding the obstacles.
Basically, the enemies, helpers, bullets are refreshed in every question.
The scores and the lives do not get refreshed until the user ends/restarts the game.

The user will move using the keyboard. 
"up", "down", "right", "left" arrows and the space bar are used.

"up"- the user moves up

"down" - the user moves down

"right" - the user moves right

"left" - the user moves left

space bar - the user shoots bullets

### C. Score

The user earns a point if he/she answers the question correctly.
The user loses a point if he/she fails to answer correctly in time.

### D. Life

The user has three lives.
There will be a bar that indicates how many life the user has.
The user loses a life if he/she hits a blocker, hunter, and guard.
When all three lives are spent, the user dies and the game ends.
Then the user has an option to close the game or the restart the game.

### E. Layout

![alt text](http://imageshack.us/a/img201/2258/boardd.png "Layout")

The layout is self explanatory.

The user's name and the score are displayed on the top left corner.
The numbers of life and bullet are displayed on the top right corner.
The statement and the time are on the top center.

Then there is the board with 'O' and 'X' and the wall.

The "play", "pause" buttons are on the bottom.

"play" - plays the game

"pause" - pauses the game

The restart button that says "restart" is located on the left bottom.
The quit button that says "quit" is located on the right bottom.

----



