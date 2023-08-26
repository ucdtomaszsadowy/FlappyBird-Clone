# FlappyBird Clone

## Description

A simple implementation of the popular game Flappy Bird using the pygame library. The bird moves vertically based on user input and the objective is to avoid the pipes that come from the right side of the screen. The game keeps track of the score which increases every time the bird successfully passes through a pair of pipes.
Features

    Dynamic bird movement with animations.
    Randomly positioned pipes that move across the screen.
    Score counter.
    Ground scrolling effect.
    Collision detection.
    Game over screen with restart functionality.

## Setup & Installation
Prerequisites:

    You must have Python installed.
    You need to install pygame library using 'pip install pygame'

Game Assets:
Ensure you have the following assets in the directory FlappyBird-Clone/img/:

    bg.png - Background image.
    ground.png - Image of the ground.
    restart.png - Image of the restart button.
    bird1.png, bird2.png, and bird3.png - Bird animation frames.
    pipe.png - Image of the pipe.

## How to Play

    1. Run the script using: python flappy.py
    2. Click anywhere on the screen to start the bird's flight.
    3. Keep clicking to keep the bird in the air. Avoid the pipes!
    4. Your score increases by one point for every set of pipes you pass through.
    5. If the bird collides with a pipe or the ground, the game will end. Click on the restart button to play again.


## Classes:

    Bird: Represents the flappy bird. Contains methods for updating its position and animations.
    Pipe: Represents an obstacle pipe. Can be a top or bottom pipe.
    Button: A general-purpose button class, used in this game for the restart button.
