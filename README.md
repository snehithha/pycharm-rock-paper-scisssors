# Rock Paper Scissors using OpenCV and Hand Tracking

## Overview

This project is a real-time Rock-Paper-Scissors game built using Python, OpenCV, and computer vision. The game detects hand gestures through a webcam and automatically determines whether the player has chosen Rock, Paper, or Scissors.

## Features

* Real-time webcam-based gameplay
* Hand gesture recognition using computer vision
* Automatic winner determination
* Interactive game interface
* Simple and user-friendly design

## Technologies Used

* Python
* OpenCV
* CVZone
* MediaPipe

## Project Structure

```text
demo.py                 # Main game file
resources/              # Images and game assets
.gitignore              # Git ignore configuration
```

## Requirements

Install the required packages:

```bash
pip install opencv-python
pip install cvzone
pip install mediapipe
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/snehithha/pycharm-rock-paper-scisssors.git
```

2. Navigate to the project folder:

```bash
cd pycharm-rock-paper-scisssors
```

3. Run the game:

```bash
python demo.py
```

## How It Works

* The webcam captures live video.
* Hand landmarks are detected using MediaPipe through CVZone.
* The number of fingers shown is analyzed to identify Rock, Paper, or Scissors.
* The computer randomly selects a move.
* The game compares both moves and displays the result.

## Future Improvements

* Score tracking system
* Multiple rounds support
* Enhanced user interface
* Sound effects and animations
* Online multiplayer mode

## Author

**Snehithha Mulugu**

## License

This project is created for educational and learning purposes.
