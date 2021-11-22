# # Introduction-


Snake Game is the common name for a video game concept where the player maneuvers a line which grows in length, with the line itself being a primary obstacle
The player controls a dot, square, or object on a bordered plane. As it moves forward, it leaves a trail behind, resembling a moving snake. In some games, the end of the trail is in a fixed position, so the snake continually gets longer as it moves. 
In another common scheme, the snake has a specific length, so there is a moving tail a fixed number of units away from the head. 
The player loses when the snake runs into the screen border, other obstacle, or itself.
Snake game is a classic computer action game, in which we control a snake to move and collect food in a map.
Which has been arround since the earliest days of home computing, and has re-emerged in recent years on mobile phones
it isn't world's greatest game, but it does give you an idea of what you can achieve with relatively simple c program, and perhaps the basis by which to extend the principles.
it can create more intresting games of your own.
Foods are provided at the several co-ordinates of the screen for the snake to eat. Every time the snake eats the food, its length will by increased by one element along with the score.
The game environment is a 3030 map. The snake starts with length one. 
At each time step the snake moves one step, and it can go straight, turn left, or turn right
 The snake hits its own body or the wall, The length of the snake gets zero, The game score gets negative. The game score does not change after 900 time units.
 The Main aim of the game is to collect the dots(Food) and avoid the obstacles (boarders, crosses, and the snake itself).
 As  you collect the food, the snake gets longer , so increasing your likelihood of crashing into yourself. when you collected enough food, you progress into the next level, where your snake gets larger.
 you get scored according to the length of the snake and the no. of 'x' obstacles in the screen. The speed increases every 5 levels.
 you get a bonus when you complete the level of 1000.

 
# # History of the game-
 
The concept of Snake Game originated from the 1976 arcade game Blockade, developed by a British company called Gremlin Interactive, which shut down in 1984. Blockade was designed as a two-player game in which each would guide their own snakes, leaving a solid line behind them.
Snake’s story begins long before it found a mass audience with Nokia.
It was first created as a concept in 1976 under the name of Blockage, and was a monochromatic two-player arcade game developed by video games company company, Gremlin Interactive. 
Similar to what would soon become Snake, it involved pressing arrow keys to move each character, wherein players would leave a solid trail behind them 
wherever they turned. To win, the player had to last the longest without hitting anything else.
This game inspired numerous iterations, such as the arcade game Bigfoot Bonkers that year; more similar concepts in 1977 by the then-leading video games company Atari; a computer-based version called Worm, programmed in 1978; and a single-player arcade game named Nibbler in 1982.
In 1997 came the landmark addition of Snake – first published by Finnish company Nokia for monochrome 6110 phones, and programmed by the company’s Taneli Armanto. It was on the off-chance that Taneli came to develop this iconic game, but he was the perfect suitor no less.
While developing Snake, Taneli and the team had some limitations.
This included the number of keys to control the game (i.e. the phone’s keypad), a limited display that meant they could use no more than 48 x 84 black and white pixels, and a small amount of memory to use on the device.
Snake was conceived in programming language C, just like many other parts of the software in handsets of the generation.
The game was “hand-written” line-by-line, and no specific tools or code generators were needed (or available) to do so.
While in the testing phase and working out how best the snake would move on the display, Taneli started to notice that it was difficult to go towards the edge of the screen and make a 90-degree turn without crashing
There are now countless games available to play on your phone and the landscape has changed entirely
It brought smiles, happiness, brain stimulation, and it was just something to do now and then – or better yet fill the time on a drab afternoon bus ride back from school.
It also showed us what can be done on a phone, perhaps making us a little bit more demanding for future years to come.


# Software requirements
Software Requirements:
OPerating system : WINDOWS 8/9/10
Application Software: TURBO C++ 2.0
Language: C computer graphics
Hardware Requirements:
Hard disk : 32GB
RAM: 128MB
processor : Any pentium Version


Many functions have been used in this Snake Game . Here, I will just list them below and describe the functions “gotoxy”, “GotoXY” and “delay” as they are some of the most important functions

void record()
void load()
void Delay(long double)
void Move()
void Food()
void Print()
void Bend()
int Score()
void Boarder()
void Down()
void Left()
void Up()
void Right()
void ExitGame()
