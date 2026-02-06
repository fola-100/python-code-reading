Repo:https:https://github.com/Daudie87/Beginner-Projects/tree/master
File:https://github.com/Daudie87/Beginner-Projects/blob/master/99Bottles.py
Core Data:
i)count
Ii)bottleTense
Function Overview:
I)lyrics()
II)secondVerse()
III)firstVerse()
DATA FLOW
lyrics()---->firstVerse()---->secondVerse()
Mental Run Simulation
python file runs the program from lyrics function,inside the function
a while loop is created that says as long has count is greater that one keep run the loop 
the firstverse function is runed inside the firstverse function 
"firstVerse = "%s %s of beer on the wall, %s %s of beer." % (count, bottleTense, count, bottleTense)"
 string are stored inside FirstVerse, 
"this (count, bottleTense, count, bottleTense) is a place holder for 
to be replacement to store the value inside count and bottleTense any time %s is seen"
and print firstVerse
the SecondVerse is runned inside the function 
this line is runned 
 secondVerse = "Take one down and pass it around, %s %s of beer on the wall!\n" % (count, bottleTense)
 and print statement outputed 
 if count is the same thing as one 
 "bottle" is saved inside bottleTense and secondverse function is called 
 count and bottleTense value is changed
 count is change again 
 and the firstverse() is called 
 with a print statement as the final output
 
 

 
 
 



