# DeadwoodGame
README

README

INTRODUCTION

This console game was implemented for a school project to apply object oriented 
concepts. 

Deadwood originated as a quirky, slightly satirical board game in which the 
players get to embrace their
inner actor and navigate around the backlots of a Western film. Players take on 
bit roles at different sets
and earn money and credits based on their performance measured in dice rolls. 
After four game days, the
winner is chosen based on money, credits and rank. In this rendition of 
Deadwood, gameplay will be
implemented by a software project complete with a User Interface for the board.

This beta console model version encompasses the business logic of the game. It 
does not have a GUI component as that will 
be implemented in the next step of the project (creating the model and 
controller). Game play takes place through
command line interaction.

The version that you have is a two player game. The first player will start of 
with the color label blue which corresponds
to a real life dice color. The turns are swapped every time a player Works, 
Acts, or Rehearses. If you move or upgrade
you will have to end your own turn by doing one of the above actions or by 
typing end. 



BETA TESTING

You (as the user) are very important to this game's success. Unfortunately, I 
cannot find every single bug. In its
beta testing phase, it is important to get rid of any bugs or oddities so that 
when I implement the model and
controller, the game business logic will be solid.

If you have any feedback or find any bugs, please see CONTACT info below to 
report. 

Thank you for your input! I hope that you enjoy playing the game!


SUMMARY

The goal of the game is for you (the player) to earn as much money and credits 
as you can by taking parts in scenes around
the deadwood board and upgrading your rank as you see fit. You can earn money 
and credits for each role you take.
The role may be an extra or a main role. Extra roles earn more for each Act, but 
at the end of a scene, main roles earn 
more in bonus pay outs.

Once a scene wraps in one room, you cannot take any of the roles in that room 
until the next day.

The game consists of 4 days. Each day is complete when you and the other player 
have gone through all of the rooms 
on the board. After this happens, the board is reset and all of the stages are 
open again. New main roles (cards) are dealt
to the rooms. At the end of 4 days of acting, scores are totaled and whoever has 
the highest combination of rank, credits,
and dollars wins.



HOW TO RUN:
In Linux: 

1)  Download the Deadwood.jar file and put it in appropriate user directory.
2)  Open your favorite console.
3)  Check to make sure permissions are set so that it can execute.
3a) If unsure, type chmod 775.
4)  Then type ./DeadwoodBeta.jar in the directory where you put the jar file.
4a) Alternatively : type java -jar DeadwoodBeta.jar
Enjoy!

In Windows:
1)  Download the Deadwood.jar file and put it in appropriate user directory.
2)  Open your windows command prompt.
3)  Check to make sure permissions are set so that it can execute.
4)  In directory where you put your file: type java -jar DeadwoodBeta.jar

COMMANDS

The following are valid commands on the console: (words in upper case are 
arguments which you must specify).

who: identifies current player in the form colorName (dollars, credits) rank. It 
also identifies any parts you are working.

where: describes where current player is, any active scenes, where you can move 
to, and what roles you can play.

move ROOM: will move current player to the room specified. 

work PART: player will take the current role

upgrade $ LEVEL : will upgrade player's rank to the level specified (between 
2-6) if you have enough money

upgrade cr LEVEL: same as above command but will use credits instead of dollars 
to upgrade

rehearse: gives player 1 rehearsal chip. This will help you succeed more easily 
when you act.

act : will allow player to perform current role

end: will end current player's turn



Basic Rules:

NOTE: Spelling and Capitalization are extremely IMPORTANT. there is no error 
checking implemented for this. 
For example : if you type
work Sleeping drunkard (role is Sleeping Drunkard)
you will not be able to take the role and your turn will be skipped because you 
didn't capitalize the 'D' in 'Drunkard'. 

1) you may only move to a room that is in your neighbor set
2) you can only take a role that is less than or equal to your player rank
3) While you are working a role, you may not move or act in another role.
4) you cannot work in a stage that has already been wrapped
5) you cannot work in a role that someone else is working on or has already 
worked on
6) when upgrading, you can only upgrade to the level that you can pay for. 
(valid levels between 2-6)
7) upgrading must only be done at the office 
8) you cannot act in the trailer, this is where you start the day 

On your turn you can:
1) move and take a role
2) move
3) do nothing
4) act if you already have a role
5) rehearse if you already have a role
6) upgrade if you are in the casting office

Upgrading Costs:
Rank:	Dollars	    Credits
2	         4           5
3          10          10
4          18          15
5          28          20
6          40          25



HELP

To view the board while you are playing, look at the board.jpeg file in the 
repo.
To view the complete rules of Deadwood: visit this link
http://www.cheapass.com/sites/default/files/DeadwoodRulesPDF.pdf

CONTACT

Please contact katymccl3@gmail.com if you have any suggestions or bug reports. I 
am very interested in your feedback.
