# Crazy-Snake-Game
Created the Snake Game using the turtle graphics library in Python.

## Functionality
Game Setup:

Creates a 600x600 pixel black game window with the title "My Snake Game."
Disables automatic screen updates for smooth animations.
Game Objects:

Snake(): Manages snake movement, growth, and resetting.
Food(): Handles the food object and its random repositioning.
Scoreboard(): Tracks and displays the score.
Keyboard Controls:

Arrow keys (Up, Down, Left, Right) control the snake's movement.
Game Loop:

Continuously updates the screen and moves the snake.
Detects collisions:
Food: The snake grows, food refreshes, and the score increases.
Wall or Tail: The game resets the snake and score.
Exit:

The game window closes when clicked.
