# Hangman Game 

## Description

Hangman is a popular word guessing game where the player attempts to build a missing word by guessing one letter at a time. 
After a certain number of incorrect guesses, the game ends and the player loses.

## Objective
Guess the word/phrase before your man gets hung!

<img src="https://github.com/kaushikvrudhula/Hangman-Game/blob/master/src/Vid.gif" width="70%" height="200%">

You can try playing the game here : https://kaushikvrudhula.github.io/Hangman-Game/

### Game play
* A word is picked randomly from the assigned js array ; the player tries to guess what it is one letter at a time.
* Number of dashes are equivalent to the number of letters in the word. 
* The player suggests a letter that occurs in the word, If the word contains the suggested letter then the dashes are filled in the blanks with that letter in the right places. 
* If the word does not contain the suggested letter, the other player draws one element of a hangman’s gallows. 
* As the game progresses, a segment of the gallows and of a victim is added for every suggested letter not in the word. 
* The number of incorrect guesses before the game ends is 10, but completing a character in a noose provides a minimum of 10 wrong answers until the game ends.
* The right answer results with a message and the player's accuracy.

#### <p align="right">--Enjoy !!</p> 






