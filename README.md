# Game of rooms
### DAY 2 Final Exercise for the [Ironhack Bootcamp](http://www.ironhack.com/)
More exercises in the main repository: [ironhack-april-2015](https://github.com/marianmartinez/ironhack-april-2015)

### Problem Description

You are going to create a game like the old fashioned MUDs.

The mechanics are as follows:

* The character starts in a room
* The description of the room is printed and after that a > symbol appears and the user must write an input
* There are 4 characters for movement "N", "S", "E" and "W"
* If the characted moves in a direction that is allowed the description of the new room is printed and the prompt for the new room is shown.
* If the order makes no sense a message must be shown and the description of the current room along with the prompt must be printed
* A room can accept other different orders

### Sample game

```

You are in a dark room. There is a door at the north
>
E

There is no exit there.
You are in a dark room. There is a door at the north
>
N

You are in the forest. There is a lot of light. There is a bear sleeping
>
S

You are in a dark room. There is a door at the north
>
N

You are in the forest. There is a lot of light. There is a bear sleeping
>
Cry

I don't understand
You are in the forest. There is a lot of light. There is a bear sleeping
>
Sing

The bear wakes up and kills you. Game over.

```