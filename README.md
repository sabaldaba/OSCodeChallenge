# OSClass

The first program is written in C language. 
The problem is: Find the first character in a String that doesn't repeat.
To test it the file has a main in which we call the function 'findFirstRepeated' that receives a String that will analyze to
answer the original question.
We use one iteration to traverse the String, therefore it has a  Θ(n) since it will always take exactly the length of the String to compute the final result.

The second program is written in C. It asks the user to enter an integer and after doing that if he/she wants to enter another one. After each input from the user the program will display the median of the list that has been constructed from all the inputs made.
To test the programm a main is made and it already call the function that calculates the median.
Since we are waiting for the user to know how many inputs he/she wants, this is a Θ(n) problem.

The third programm takes an N an K integers. Creates a list of k integer that goes from 0 to N-1 inclusive. That list is going to be called the prohibited list. After doing so we create a function that is going to create a new list that generates RANDOMLY the missing integers, the ones not contained in the prohibited list.
This is a bit more tricky problem to solve. We have O(n^2) since depending on the value generated by our random number generator it may or may not need to perform multiple iterations. 
