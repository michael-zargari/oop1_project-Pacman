# oop1_project-Pacman
oop1 final project - clone of the game pacman

# General Explanation:
In this exercise, I implemented the well-known Pacman game. The goal of the game is to progress through the stages and avoid the ghosts who tries to stop you from eating the cookies. I created three stages with different difficulty levels and tried to incorporate as much gameplay as possible while applying the knowledge I gained in class.

# Game Progress:
In each stage, there is a number of cookies that the player has to eat. To pass a stage, you have to eat all the cookies in that stage. There are several obstacles during each stage, such as doors that will prevent you from accessing a room, unless you eat a key (and than a random door will open). There are also walls that cannot be passed through and a ghosts that will try to prevent the access to the cookies.

# How to add another stages(manualy):

If you want to add stages beyond the three stages that were created, you can enter a to the text file - "GameLevelTxt" which can be found in the resource file.
Than to specify the stage's size and the time, for example:

30 15 1

The first parameter (leftmost) represents the stage's width, the second parameter represents the stage's height, and the third parameter represents the time (in minutes) for the stage. 

Skip a line and add the game table at the end. 
Make sure to leave an empty line before the end of the file to signal the program that there are no more stages to read.

Index:

'#' Wall
'a' Player
'&' Demon
'?' Time
'@' Extra Life Gift
'$' Super Transformation Gift
'!' Freeze Gift
'D' Door
'%' Key

These are the symbols used to indicate the different elements in the game.
 
