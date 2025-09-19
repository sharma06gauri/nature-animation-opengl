# Nature Animation using OpenGL functions

## Overview
This repository contains a mini-project for creating a simple, animated nature scene using **OpenGL functions**. The project was submitted in partial fulfillment of the requirements for the VI semester Bachelor of Engineering in Computer Science and Engineering at Visvesvaraya Technological University, Belagavi.

The program creates an interactive scene that includes a sun, clouds, hills, a river with boats, trees, houses, and a fence. Users can control the movement of the clouds and boats using keyboard inputs, mouse clicks, and a right-click menu.

## Features
- **Animated Elements:** Clouds and boats move horizontally across the screen, adding a dynamic feel to the scene.
- **User Interaction:**
    - **Keyboard Input:** Start or stop the movement of boats and clouds, and exit the program using specific key presses.
    - **Mouse Clicks:** Left-click toggles cloud movement, and right-click toggles boat movement.
    - **Menu:** A right-click menu provides options to control the movement of both clouds and boats.
- **Scene Composition:** The scene is built using various OpenGL primitives and functions to draw shapes like polygons, rectangles, and circles.

## Technologies Used
- **C/C++:** The core programming language for the project.
- **OpenGL:** The primary graphics library used for rendering 2D and 3D graphics.
- **OpenGL Utility Toolkit (GLUT):** Used for window management and handling user input.
- **FreeGLUT/OpenGLUT:** Specific implementations of the GLUT library.

## Hardware & Software Requirements
### Hardware
- **Processor (CPU):** Multi-core processor (e.g., Intel Core i9 or AMD Ryzen 9)
- **RAM:** A minimum of 32 GB is recommended.
- **Storage:** At least 1 TB SSD for fast data access.
- **GPU:** A high-performance graphics card (e.g., NVIDIA GeForce RTX 3080/4090 or AMD Radeon RX 6800 XT).
- **Monitor:** A high-resolution monitor (4K) with accurate color reproduction.
- **Peripherals:** High-precision mouse and ergonomic keyboard.

### Software
- **Operating System:** Windows, macOS, or Linux.
- **Compiler:** C/C++ compiler like GCC (for Linux) or MinGW (for Windows).
- **Libraries:** OpenGL and GLUT (e.g., FreeGLUT).
- **Build Tool:** `make` utility for Unix-like systems.

## Project Structure
- `src/` : Contains the source code file(s).
- `docs/` : Contains the project report (PDF).
- `assets/` : Contains any images, snapshots, or other media related to the project.

---

### 📂 Directory Structure

You should organize your project files into a clear directory structure.

-   `nature-animation-opengl/`
    -   `src/`
        -   `main.cpp` (or a similar name for your C/C++ source code)
    -   `docs/`
        -   `finallllnochange (2).pdf`
    -   `assets/`
        -   `front_sheet.png` (or a similar name for the front sheet snapshot)
        -   `final_view.png` (or a similar name for the final view snapshot)
        -   ... other snapshots from the report ...
    -   `README.md`
    -   `.gitignore` (optional, but recommended to ignore build files)
    -   `Makefile` (optional, if you're using a build utility)
