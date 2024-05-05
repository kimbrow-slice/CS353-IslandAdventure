# Island Adventure Game

During your voyage across the sea, you notice a storm brewing ahead. The crew feels anxious, however, the treasure aboard is far too valuable to reoute now. 
As the waves begin to crash louder... and lightening cracks... you find yourself lost in uneasy water. Enjoy your adventure! 

## Game Features
- Travel to 4 unqiue locations: coastline, shipwreck, cave, and cliffside.
- Decision based outcomes influence the games progression and endings.
- d6 and d8 dice mechanics for actions and events that add an element of chance to the game. 
- Use directional commands such as (north, south, left, right).
- Start with an empty inventory.
- Find 4 items which optionally can be dropped: boots, gold, helmet, rope.

## References
- [Making a better mousetrap](https://queue.acm.org/detail.cfm?id=2068896)
- [Racket Dice roll](https://www.reddit.com/r/learnprogramming/comments/qmelu/first_time_racket_programmer/)


## Setup
1. Clone the repository to your local machine e.g., `git clone https://github.com/username/island-adventure.git`
2. Open the game file in DrRacket or another Racket-friendly IDE.
3. Ensure all game scripts and resource files are located in the same directory as the game's main script.
4. Execute the game by pressing 'Run' in your IDE.
5. Follow the on-screen instructions to start your adventure.

### To Do:
1. If user has rope in inventory, add +2 to their cliffside roll. 

### Console Instructions after running the game
- Use direction commands (`north`, `south`, `east`, `west`) to move within each of the locations. 
- Use `inv` to display your current inventory and `drop item name` to remove items.
- Additional commands like `help`, `proceed`, `yes', and `no`.

### Game Start
![Game Start ](/GameStart.png)

### Help commands
![Help Commands](/HelpCommands.png)

### Game Play: ENDING 1 : "Your low dexterity causes you to slip and fall to your death." : 1-3 roll DEATH
![Game Play Ending 1](/GamePlayDeath.png)

### Game Play: ENDING 2 : "You fall but a bush breaks your fall..." : 3-6 roll
![Game Play Ending 1](/GameEnding2.png)

### Game Play: ENDING 3: "You successfully climb the cliff and see a search party!" : 7+ roll WIN CONDITION
![Game Play Ending 1](/GameEnding3.png)
