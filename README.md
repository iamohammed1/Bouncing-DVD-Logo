# Bouncing DVD Logo Simulation

**Author**: Mohammed Al-Mokhtar  
**Email**: mohammed.a.mohtar01@gmail.com

## Description

This project simulates the classic bouncing DVD logo animation using Python. The program displays multiple DVD logos that bounce around the terminal window, changing direction and color whenever they hit the edges or corners of the screen.

## Features

- The DVD logos move diagonally across the terminal.
- The logos change color upon hitting an edge or corner.
- The program keeps track of the number of times a logo hits a corner.

## How to Run the Program

### Prerequisites

- **Python 3.x**
- **bext** module

### Installation

1. **Install the `bext` Module**:
   This program requires the `bext` module. You can install it using pip:
   ```bash
   pip install bext
   
Clone the Repository:
git clone https://github.com/iamohammed1/Bouncing-DVD-Logo-Simulation

Navigate to the Project Directory:
cd Bouncing-DVD-Logo-Simulation

Navigate to the Project Directory:
cd Bouncing-DVD-Logo-Simulation

Run the Program:
python DVD_bouncing.py

Executable Version
If you prefer not to run the Python script, you can download the executable version of the program from this link.

Example Code
Here's a small snippet showing how the program initializes the DVD logos and handles their movement:
logos = []
for i in range(NUMBER_OF_LOGOS):
    logos.append({COLOR: random.choice(COLORS),
                  X: random.randint(1, WIDTH - 4),
                  Y: random.randint(1, HEIGHT - 4),
                  DIR: random.choice(DIRECTIONS)})
    if logos[-1][X] % 2 == 1: 
        logos[-1][X] -=1

Requirements
Python 3.x
bext module (pip install bext)
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or suggestions, feel free to contact me at mohammed.a.mohtar01@gmail.com.

