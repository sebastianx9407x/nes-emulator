# NES Emulator

Following OneLoneCoder's tutorial on building an NES Emulator.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This project is a NES emulator built by following the tutorial series by OneLoneCoder. The emulator aims to replicate the functionality of the original Nintendo Entertainment System, allowing users to play classic NES games on modern hardware.

## Features

- Emulates CPU, PPU, and APU of the NES
- Supports popular mappers (MMC1, MMC3, etc.)
- Accurate timing and rendering
- Save and load game states
- Support for various input devices

## Installation

To get started with the NES emulator, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd nes-emulator
    ```

2. **Install dependencies:**
    Ensure you have a C++ compiler and the necessary libraries (e.g., SDL2) installed.

3. **Build the project:**
    ```bash
    mkdir build
    cd build
    cmake ..
    make
    ```

## Usage

1. **Run the emulator:**
    ```bash
    ./nes-emulator <path-to-rom>
    ```

2. **Keyboard Controls:**
    - `Arrow keys`: D-pad
    - `Z`: A button
    - `X`: B button
    - `Enter`: Start
    - `Right Shift`: Select
    - `Esc`: Exit emulator

3. **Loading and saving states:**
    - `F5`: Save state
    - `F7`: Load state

## Acknowledgements

- Thanks to OneLoneCoder for the excellent tutorial series on building an NES emulator. You can find the tutorial [here](https://www.youtube.com/playlist?list=PLrOv9FMX8xJE8NgepZR1etrsU63fDDGxO).
- Inspiration and guidance from various emulator development communities.
