# Snake-Game
Snake is represented by a rectangle shape using pygame.draw.rect method , has some velocity for moving and will be changing using pygame.time.clock method and present on game window in any random position .
Food of snake also has same shape and co-ordinates that snake has. Everytime the snake accomplish to eat food it's length will increase and the position of food change randomly using random.randint method.
If the snake goes out of the game window or collide with itself the game over msg will display.
Score and high score will also display on the screen. 
For high score, highscore text file is imported in the main program file and can be read and write.
