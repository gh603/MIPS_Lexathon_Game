# MIPS_Lexathon_Game
This is a course project of "Computer Architecture". The project is to implement the Lexathon game using MIPS.
Lexathon, is a 9-letter search game for users. From a grid of 9 letters, users should discover as many words as possible of 4 or more letters that contain the central letter in the grid. Every word users find gets users more time and increases their score. 

#Important features of this game. 
	-Linked List is chosen to place every word in the dictionary for easy traversal and fast access to each word. 
	-Function to retrieve words from a dictionary and store words into the Linked List. 
	-Function to compare words given the starting address of words. 
	-Function to find all possible words using the nine letters in the grid from the dictionary. 
	-Function to shuffle games by generating a new grid containing 9 new random letters. 
	 A random word of nine letters is firstly selected from dictionary, and the nine letters in the word are used to construct the grid.
	 The purpose to randonly select a nine-letter word is to guarantee that at least there is one valid word that could be formed from the grid. 
	-Function to present console to users. 

#File Description: 
	1.Lexathon.asm: The MIPS code for this project. 
	2.randomDict.txt: a reduced set of dictionary used in this project. 