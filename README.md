# Recursion

//Q.  What is Recursion ?
// Ans. Recusion is nothing but the function which is calling to itself untill the specific condition is not met.

//Q.  How to solve problems using Recursion?
//Ans. First and formost one, we need to find out the base case of that problem.

//Q. What are the 2 main basic rules of recursion ?

**Rule 1:**
// Base case: Base case is nothing but the point where you have to stop. 
// For Example: I want to print the counting of n numbers so my base case here at which no i have to stop.

**Rule 2:**
//Recursive call should align towards the base case.Otherwise it will never reach the base case and that's why it will never end. In short, program will be crashed.

//Q. What are the different types of Recursion ?
// Ans. There are basically 2 types of recursion
**_1. Head recursion_**: In head recursion the recursive call will be made first and then the logic of the function is executed.

**_2. Tail recursion_**: But in tail recursion the logic of the function will be executed first and then the recursive call will be made at the end.


**Disadvantages of recursion**
Recursive functions are generally slower than non-recursive function.
It may require a lot of memory space to hold intermediate results on the system stacks.
Hard to analyze or understand the code.
It is not more efficient in terms of space and time complexity.
