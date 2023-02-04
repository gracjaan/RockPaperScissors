# Rock-Paper-Scissors Game using Hand Detection

This code implements a Rock-Paper-Scissors game that uses computer vision to detect hand gestures as inputs. The game involves two players, AI and the user, and each round one of the players makes a hand gesture representing either rock, paper, or scissors. The hand gestures are detected using the HandDetector module from the cvzone library.

## Prerequisites
Before running the code, make sure you have the following libraries installed:

* opencv-python
* cvzone
* numpy

You can install these libraries by running the following command in your terminal:

`pip install opencv-python cvzone numpy`

## Running the code
To run the code, simply run the following command in your terminal:

`python main.py`

Make sure you have a webcam connected to your computer.

## How to play
To start a game round, press the 's' key. The game will display a timer counting down from 3 seconds, during which you can make a hand gesture. The AI will also make a random gesture at the same time. Once the timer finishes, the game will show the result of the round, including which player won and the updated score for each player.

## Game rules
* Rock beats Scissors
* Scissors beats Paper
* Paper beats Rock

## Scoring
A player earns 1 point for winning a round
The game continues until a player reaches 5 points, at which point they are declared the winner.
