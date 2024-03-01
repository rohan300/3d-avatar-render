# 3D Avatar

This repository contains the code for my 3D avatar app built with React Three Fiber.

## Overview

The app displays a 3D human avatar model loaded from a GLTF file. It uses React Three Fiber for rendering and animation. 

The avatar has two animations:

- Typing - loaded from an FBX file
- Idle standing - loaded from another FBX file

It uses drei's useGLTF, useFBX, and useAnimations hooks to load and play the animations. 

The avatar's head follows the mouse cursor position using React Three's useFrame hook.

## Running Locally

To run the app locally:

1. Clone this repo
2. Install dependencies

    ```
    yarn 
    ```

3. Start local dev server

    ``` 
    yarn dev
    ```

## Components

- **Experience** - Sets up canvas and camera
- **Avatar** - Renders the actual 3D avatar model and animations

## Credits

Created model using <a href = "https://readyplayer.me/">ReadyPlayerMe </a>

Typing and Idle animation from <a href = "https://www.mixamo.com/#/">Mixamo</a>

<img width="1466" alt="Screenshot 2024-03-01 at 3 25 03 PM" src="https://github.com/rohan300/3d-avatar-render/assets/46117360/aab101f0-ec36-4f3e-9f4f-464c05e9179e">

