# languagedetection-



What small problems do we need to solve?

Break up text into two vectors and calculate each files trigram frequency 
using a function that compares each frequency to each other using the equation given in the handout.


Libaires:
string 
cmath 
vectors 
stdlib
header file 
iosteam
fstream 


Classes:
langue class that encludes method functions:
- To get header file that contains langue files and if file contains uppercase letters throw runtime error.
- Break two files up into separate vectors infile open function with loop.
- Function to return just the letters for each vector.
- Function that loops through vector and return new vector of each letters index in the ascii table for each vector.
- int type function to calculate the frequency index in ascii multiplied by 27 to the n-1 plus each other letter in the trigram to n-1 returns tri gram frequency (n declared at 3).
- Private part of class to store trigram frequency of given data for the program to learn from as well how many trigrams appear in a test document 
- Bool type comparison function to compare both trigram frequencies using recursion to find n-1 using the similarity equation return true with closest test file. 



Main for milestone 1:
use methods in the class to return the trigram frequencies of test file and files we have already learned 



Main for milestone 2:
Main will include all files and will also compare the two vector trigram frequencies and use machine learning to detemine which langue the vector is. 

Files:
All test files
.cpp files
.h files

Compile: 
we base it off a pervious assigments and fix it based on the assignment. 











