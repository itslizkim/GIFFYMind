# GIFFYMind

![login](login.gif)

## Introduction
Welcome to GIFFYMind, a remake of the MasterMind game. GIFFYMind is a single-page application written with React JS.
Website: https://giffymind.netlify.com/

## Game Rules

![game play](game.gif)

At the beginning of each game the computer generates a secret code of four gifs. The gifs are always chosen from the same eight gifs. Duplicates are allowed, so the computer could even choose the same gif four times.

Your objective is to guess the secret code. You will have to guess the gif and put them in the same order as they are in the secret code.

Choose four gifs in the next available row and then click on the Check button. The computer will score your guess in the following way:

- For each guess that is right in both gif and position, you get a green point
- For each guess that is right in gif but not in position, you get a yellow point
- For each guess that is wrong, you get a white point

You have ten chances to make your guesses, if you exhaust all of them without guessing the code, you lose the game.

Good Luck!

## Dev Tools
- Front End:
  - `bootstrap` - serves as the base for this app's css structure

- Back End:
  - `Rails` - hosts the database server
  - `Giphy` - serves as source for this app's gifs
