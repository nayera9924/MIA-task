This is a Wordle like game built in Python.
The program randomly selects a 5 letter word from a dataset (words.txt) and the player has 6 tries to guess the word.
the program gives green color to the letter if it is inthe word and in the right place ,yellow color if the letter is in the word but in the wrong place and gray color if the letter isn`t in the word.

import random from libraries to selesct the target word randomly
for loop as the player has 6 tries, on each loop:
-input word from user
-validate word length=5
-cheak if the word is in the dataset
-compare each letter of the word to the target word and give them the colors
if the user enter the target word, display "you win"
if user yhe user give up, display the target word.
if the user use the 6 tries, display "you lost"
