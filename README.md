# Pac-Man Game

This Pac-Man game is a classic arcade-style game implemented using pure JavaScript. The game involves controlling the iconic Pac-Man character to eat all the pac-dots and power pellets while avoiding the ghosts.

## Features

- **Movement**: Pac-Man can be controlled using the arrow keys to move up, down, left, or right within the grid. The movement is constrained by walls.
- **Objective**: The objective of the game is to eat all the pac-dots and power pellets on the grid while avoiding the ghosts. Eating pac-dots increases the player's score.
- **Power Pellets**: Eating power pellets temporarily allows Pac-Man to eat the ghosts, adding extra points to the player's score.
- **Ghost Behavior**: The ghosts move randomly around the grid, changing direction when they encounter a wall or another ghost.
- **Game Over / Win**: The game ends if Pac-Man collides with a ghost without eating a power pellet. If Pac-Man eats all the pac-dots and power pellets (reaching a score of 274), the player wins.
- **UI Elements**: The game includes UI elements such as a score display, start screen, game over screen, and win screen to provide feedback to the player.

## Technologies Used

- **HTML/CSS**: Used for structuring the game layout and styling.
- **JavaScript**: Implemented the game logic, including character movement, collision detection, scoring, and game state management.

## Implementation Details

- **Event Listeners**: Event listeners are used to detect keyboard inputs to control Pac-Man's movement and start the game.
- **Game Loop**: The game employs a game loop to continuously update the game state and handle character movement.
- **Classes**: JavaScript classes are utilized to define the Pac-Man character and the ghosts, encapsulating their properties and behavior.
- **Grid System**: The game is based on a grid system where each cell represents a part of the game environment, allowing for easy movement and collision detection.

## How to Play

1. **Starting the Game**: Press the Enter key to start the game.
2. **Movement**: Use the arrow keys to control Pac-Man's movement within the grid.
3. **Objective**: Eat all the pac-dots and power pellets while avoiding the ghosts.
4. **Scoring**: Eating pac-dots increases your score. Eating power pellets allows you to eat ghosts for additional points.
5. **Game Over / Win**: The game ends if Pac-Man collides with a ghost without eating a power pellet or if all pac-dots and power pellets are eaten.
