# Angry Bird Game using Python and Pygame

## Project Description

This is a simple Angry Bird-like game developed using Python and the Pygame library. The game features physics-based interactions between birds, pigs, and blocks, multiple levels, and an interactive menu. The goal is to strategically launch birds to destroy pigs and clear levels.

## Features

-   **Physics Engine**: Custom-built physics for realistic projectile motion and collisions.
-   **Multiple Levels**: Progress through various challenging levels.
-   **Interactive UI**: Buttons for starting the game, quitting, pausing, and restarting levels.
-   **Customizable Assets**: Easy to change background, ground, and character images.
-   **Dynamic Gameplay**: Pigs and blocks react to collisions and can be destroyed.

## Installation

To run this game, you need to have Python and Pygame installed on your system.

1.  **Clone the repository (if you haven't already):**
    ```bash
    git clone https://github.com/shyam1444/angry-birds-pygame.git
    cd Simple-Angry-Bird-Game-using-Python
    ```

2.  **Install Pygame:**
    If you don't have Pygame installed, you can install it using pip:
    ```bash
    pip install pygame
    ```

## How to Run the Game

After installation, navigate to the project directory and run the `index.py` file:

```bash
python index.py
```

## Recent Enhancements

-   **Beautiful Background**: The game now features a visually appealing cartoon-style background image instead of a solid color. This was implemented by loading `background.png` and blitting it across the screen in the main game loop and map drawing functions.
-   **Detailed Ground Texture**: The plain ground has been replaced with a textured image (`ground_texture.png`) to give it a more natural and enhanced look during gameplay.
-   **Improved Text Visibility**: The colors of the menu text and in-game UI elements (score, birds remaining, pigs remaining) have been changed to black for better contrast and readability against the new background.
-   **Red Bird Marker**: The projectile path marker for the bird, indicating where it will go, has been changed to a bright red color for better visibility.

## Future Enhancements

Here are some ideas to further enhance the game's visual and interactive experience:

-   **Dynamic Background Elements**: Implement parallax scrolling for the background, where different layers move at varying speeds, creating a sense of depth.
-   **Particle Effects**: Add subtle particle effects for impacts and destructions (e.g., when a bird hits an object, or a block is destroyed) to make interactions more dynamic.
-   **Improved UI/HUD**: Enhance the graphical elements of the score display, bird/pig counters, and other UI components with custom frames, icons, or animated elements.
-   **Sound Effects and Music**: Integrate background music and specific sound effects for various in-game actions (bird launch, pig destruction, block breaking, level cleared/failed) to boost immersion.

**Special Thanks for Assets:**
-   Background Image: [Cozy Endless Game Background](https://opengameart.org/content/cozy-endless-game-background)
-   Ground Texture: [Seamless ground texture by hhh316](https://www.deviantart.com/hhh316/art/Seamless-ground-texture-183190001)

Feel free to contribute or suggest further improvements! 
