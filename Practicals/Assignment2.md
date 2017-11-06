Manipulating files

Introduction

The aim of this second session assignment is to practice the use of the basic file handling command lines ranging from files creation, editing and extracting information from them.

Tools used in this session

If you do have a Linux system installed in your machine, make use of your system terminal. If you are a windows user, we highly recommend the use of the Cywgin tool (https://cygwin.com/index.html). You can find more information about the Cywgin installation via this link: https://cygwin.com/install.html
Some of the commands (nano and wget) we will be using need extra packages installations for Cygwin, if it’s not already done, no worries, it takes few minutes. 

Always remember these rules while working with the Linux terminal
•	Make sure you separate your command name, arguments and options using spaces
•	Each option is preceded by - (examples: -l, -r, -lh)
•	You can combine different options: -lh for example means a combination of -l and -h
•	Linux is case-sensitive: A and a are different (it’s not the case for Cygwin and some Mac OS terminals)
•	Make use of these Wildcards while working with the command lines

Task 1: Create your own files and manipulate them!

Task 1: Instructions
We will be using the same file structure (Assignment1_FilesStrcture.png) you have created. Make sure you are in the right directory each time or specify the absolute or relative paths to the files you are dealing with.

1.	Open a terminal in your computer 
2.	Create a new directory "assignment" under your Session2 directory
3.	Create with nano 2 different files genes1 and genes2 under assignment (no need to copy paste the result into your assignment form)

The content of genes1
gene1 4
gene3 66
gene7 6
The content of genes2
gene1 4
gene2 6
gene4 66

4.	Copy genes1 under the directory Session1
5.	Rename the copy of genes1 (that is under Session1) to test1 
6.	What would be the result of tail -n2 genes2?
7.	What would be the result of head genes1? Explain
8.	Create with touch 3 different files under assignment: genes3, genes4, genes5
9.	Copy the newly created files as well as genes1 and genes2 using the wildcards into the directory Session1




