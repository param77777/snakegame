# Snake Game 🐍

This is a classic Snake Game implemented using Python's `turtle` graphics library. The objective is to control the snake to eat food while avoiding collisions with the walls and its own tail.

## Features
- **Dynamic Gameplay**: The snake grows in size as it consumes food.
- **Collision Detection**: The game ends when the snake collides with the walls or its own tail.
- **Score Tracking**: Displays the current score and a game-over message.
- **Keyboard Controls**: Use the arrow keys (Up, Down, Left, Right) to control the snake.

## Prerequisites
To run the game, you need to have Python installed, along with the following libraries:
- `turtle`
- `random`
- `time`

## Controls
- **Arrow Keys**:
  - Up: Move Up
  - Down: Move Down
  - Left: Move Left
  - Right: Move Right

## Files in the Project
- **`main.py`**: The main script to run the game.
- **`snake.py`**: Contains the Snake class to manage the snake's behavior and movement.
- **`food.py`**: Contains the Food class to generate and refresh food.
- **`scoreboard.py`**: Contains the Scoreboard class to manage the game's score and display game-over messages.

## How the Game Works
1. The game starts with a snake, a food item, and a scoreboard.
2. The snake moves continuously, and the player uses the arrow keys to change its direction.
3. When the snake eats food:
   - It grows longer.
   - The score increases.
4. The game ends if:
   - The snake collides with the wall.
   - The snake collides with its own tail.

## Future Improvements
- Add levels with increasing difficulty.
- Implement a high score feature.
- Incorporate sound effects.

## Author
Created by **Tallapalli Parameswara Reddy**.
