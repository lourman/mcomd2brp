# Lab 1 – Recap of Skills from Year 1

## Task 1: Precedence and Associativity

While programming there would be multiple times that bugs arise from simple precedence or associative mistakes. Using the operator precedence and associativity rules used in C# describe how the compiler would evaluate each of the following expressions:
1. x=y=z=10
2.
Forx=1,y =4 Evaluate: x *= ++y + 2;
3.
Forx=1,y =100,z =10,i =1,j =2,k =-1 Evaluate: (x+y/ z-i*j)*k
4.
Fora=false,b =true, c=false,d =falseEvaluate: a||b&& c||d
First try them on paper then verify your solutions by writing a console program to check if you found the correct answers.

## Task 2: Loops and Methods

Write a C# console application that takes as an input a positive integer number (a). Your program should be able to calculate if the number is a prime and output “prime” or “not prime” accordingly. The program should keep asking for numbers until the user inputs a 0 (zero). For each integer given as input:
•
If integer is a 0 (zero) exit program else continue
•
Make sure it is a valid number
•
If valid fnd if it is a prime number
•
Depending on the result output a string with the value “Prime” or “Not Prime”
•
Start process again

Constraints
0 ≤ a ≤ 232 − 1

Example Output:
input:Enter a number to determine if it is a prime number: 
input: 24 
output: 24 is not a prime number 
output: Enter a number to determine if it is a prime number: 
input:3 
output:3 is a prime number 
output: Enter a number to determine if it is a prime number: 
input:-293 
output:Enter a number to determine if it is a prime number: 
input:0 
output:Thank you for using our prime number checker

## Task 1: Coffee Bar V0 – Improving the Code extensibility

1)	Download and extract the project CoffeeBarV0 from Blackboard
2)	Run the program and make sure you understand how it works
3)	Determine a quick way of adding the item ‘Milk’ at a cost of 40p to the system. Record which code you change and check the system works.
4)	Add another customer ‘Paul’ with a balance of £99.75. Which code was changed to make this modification to the functionality?
5)	Think about how you would change the way the system is written in regard to the items for sale so that it is more similar to the way the customer system works. Make the changes.
6)	The code is the event handler for the button is not well structured in that it attempts to work with the user interface AND do the functionality of adjusting the balance. Write at least one additional method to separate this out. 
7)	Save this code and bring a copy of the code to the seminar. 

## Task 2: Adding functionality to add the balance
1)	At the moment balances only go down. Using good coding practice add functionality to allow the balance of the Customer to be increased by the denomination of one of the notes £5, £10 or £20.
2)	Save this code and ensure it’s available in the seminar.

##Task 3: Errors in the Code
1)	Add this line of code into any part of the event handler uiItemsCombo_SelectedIndexChanged
Balances[current_customer_index] += 1m;
	What is your opinion of this code? Is this simply a bug that needs removing, or is it bigger problem than this?
	
## Task 4: Coding Standards 
In blackboard you will find information and links about naming conventions, coding standards and user interface good practices. Try to apply these standards, conventions and good practises to your final project.
After you finish this consider these questions:
1)	How much time did it take you to do this?
2)	Was it worth it?
3)	What will you change the next time?

