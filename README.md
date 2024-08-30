# The Maze
The Maze is an immersive 3D maze game that transforms a simple 2D map into a dynamic and navigable 3D world using ray casting techniques. Whether you're exploring the intricate pathways or racing against time, The Maze offers a unique challenge that tests both your problem-solving skills and spatial awareness.

The Maze was meticulously crafted in C using the powerful SDL2 library. The development was conducted on Ubuntu 24.04, leveraging the capabilities of gcc (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0 for compilation. The project emphasizes performance, precision, and a deep integration with low-level hardware access to deliver a smooth and engaging gameplay experience.

## About SDL2
Simple DirectMedia Layer (SDL2) is a robust, cross-platform development library designed to provide low-level access to essential components like audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. This library is widely used across the gaming and software development industry, powering everything from video playback software and emulators to some of the most popular games in the market, including Valve's award-winning catalog and many Humble Bundle titles.

## Unique Features
Dynamic Lighting and Shadows: Implement real-time lighting effects that respond to player movement, adding depth and realism to the maze environment.
Adaptive Difficulty: The maze's complexity can adjust based on the player’s performance, ensuring a continually challenging experience.
Time Trial Mode: Race against the clock to complete the maze in the shortest time possible, with leaderboards to compare your best times with others.
Hidden Secrets: The maze contains hidden passages and secret rooms that can only be discovered by keen-eyed players.
Customizable Controls: Players can remap controls to suit their playstyle, offering greater accessibility and comfort.
Installation

To get started, clone the repository using the following command:

```
sh
Copy code
$ git clone https://github.com/lilahseyfu/Maze-Project
Usage
Launch the game and start your adventure:
```

Execute ./maze or type make run to start the game.
Movement Controls:
Use the up and down arrow keys (or w and s) to move forward and backward.
Use the right and left arrow keys (or d and a) to rotate the camera around.
Compilation
Compile the source code with the following command:

sh
Copy code
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
Flowchart
Visualize the game's logic and flow:

Demo
See The Maze in action:

## Future Enhancements
Multiplayer Mode: Compete with friends in a multiplayer maze race.
VR Support: Experience the maze in virtual reality for an even more immersive gameplay experience.
Advanced AI Opponents: Add computer-controlled opponents to race against in single-player mode.


``` Author Khalid Sinteayehu ```
Crafted with dedication and a passion for game development.





