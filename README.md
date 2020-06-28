### Program Design
    This step is used in industry and its when we keep on repeatedly run, modify and review a program until it is up to standard and does serve its purpose of creation. The bottom line is that it is bug-free and does perform the task we want it to.
### Pseudocode
    A very thorough explanation and what a computer program or algorithm must perform to complete the desired task.
    It is written in a way for everyone to under e.g. I am printing the value of x to the console.
### Arithmetic Operators:
    +,-,*,/,%,**
### Arrays
    data structure which can store a fixed or unfixed(using a variable) size of elements within it
### Array Methods
    1-.add
    2-.remove
    etc.
### Assignment Operator: 
    =
### Assignment vs Equality(In Data type and value e.g. 1 "1" with = it would print true but with === print false
    (= vs == vs ===)
### Asynchronous
    The ability to execute more than one element at a time
### Branching Statements
    using the keyword break, continue, return
### Camel Case
    blaBlaBla the first letter of the first word is lower case, but the first letter of any subsequent word is uppercase
### Comparison/Relational Operators:
    ==, < , > , <= , >= , !=
### Conditionals(if this happens then do this).
    If this conditions evaluates to true execute this piece of code. 
### Constants and Variables:
    Immutable vs Mutables. Meaning Should I enforce an error to be raised if the value is modified or allow it
    to be changed
### Data Type Conversions(casting or type coercion):
    changing a variable from one data type to another
### Derived Data Types: 
    When you define class. You use these tools: Pointers, Arrays, Structures, Classes, Union, Enumeration, etc.
### Data Types
    char c= 'c' //this is a Character data type it is denoted in single quotes. It takes 1 byte in memory
    int a = 5; //this is an Integer it has no decimal. It takes 4 bytes in memory.
    float b= 1.234567 // this is called a Float it has a fractional portion and can have up to 7 sig figs past the decimal. It takes up, 4 bytes in memory. 
    double d= 18.494483923923 //This is a Double it has a fractional portion and is more precise than a float.
    It can have up 15 decimal places in precision. It takes up 8 bytes in memory
    
    string d= "Hello" //this is a String or an array of characters it is denoted in double quotes. It takes up 2 bytes in memory
    bool e= true //this is a boolean it can have 2 values either True or False. 1 meaning True and False meaning 0. It takes up 
    	#include<iostream>
	using namespace std;
	main()
	{
    		bool x= true;
    		cout<<x;
	}
	
	//THIS OUTPUTS 1.
### Dynamically-typed
    The data type of a variable is checked at run-time(Python, Ruby,JavaScript, PHP)
### Flowcharts: 
    Diagram that informs the public what logic your program is following
### Functions:
    we create a function to make our lives easier and make our code shorter and remember the bottom REUSABILITY
### Identifier Names:
    myName, hisName
### If Then Else Structure
    IF a certain condition is met do this. Else do this.
### Indexing
    position of an element in an array 1st element is at index 0. The last element is one less than the size of the array
    
    Another way to access the last element of an array is by entering arrayName[-1]
### Input and Output:
    Input is what I send to the compiler and output is what I get back
### Integrated Development Environment: 
    The application that build and runs our programs
### Iteration
    How many times do I want the program to loop through my piece of code. 
### Linked Lists
    A chain of elements which are connected to its predecessors. The elements are called nodes.
### Lists Vs. Tuples
    Lists can be used to store data similar to arrays and are mutable whereas tuples are immutable
### Loosely-typed/Weakly-typed
    Specifying the data type of the variable/object upon declaration is not enforced
### Members
    I create an array of integers say 4,5,6 and I give it a name of myArray 5 is a member of of myArray
### Method:
    A function that is part of a class is referred to as a method. However, in other programming languages a function that is       not part of a class is referred to as a function. 
    All java classes should have an access modifier(e.g. public, private and protected). Within a main class we have a main method
### Modular Programming:
    software design technique that emphasizes separating the functionality of a program into independent, interchangeable modules
### Nested Loops 
    a loop within a loop
    for(int i =1;i=3;i++)
    {
	for(int j=1;j<3;j++)
	{
	    cout<<b[i][j];
	}
    }
### Parameters and Arguments: 
     void add(int i, int j)
     {
            cout<<i+j<<endl;
     } 
     add(4,5) ..... In this case i and j are the parameters they are your functions signature and 4 and 5 are your arguments.
### Pascal Case
    BlaBlaBla meaning the first letter of every word in the identifier is upper case

## Pass by Value vs Pass by Reference: 
### Pass By Value:
    make a copy of the value in memory e.g. example above 4 and 5 are copied to memory. When I want to use the parameter for a computation
### Pass By Reference:
    keep a log of the variable's location in memory so that I don't want soemthing to be changed.


### Primitive Data Types:
    Int, Float, String, Boolean, Double,Char
### Programming Paradigms
    1- Functional: We break a problem into subsets. Every subset will have its designated function that will 
    solve it in implementation
      
    2- Object Oriented: We have different classese each class is in charge of a task to perform and the scope 
    is at the class's discretion
      
    3- Imperative: computation is performed in a sequence of steps similar to a recipe
      
    4- Logical: make assertions about a situation, lay out the facts we maintain data and tackle 
    the problem by deduction similar to process of elimination

### Return Condition(Value or Void):
    Do I want something to be returned to me back in the console(return) or not(void).

### Scope(Who can access what):
    Control who has access to certain elements within my application public, protected and private.

### Statically-typed
    The data type of a variable is checked at compile-time(Java, C, C++, C#)

### Synchronous
    Execute one element at a time

### Strongly-typed
    Specifying the data type of the variable/object upon declaration is strictly enforced. If not performed, the compiler will throw an error to the console.

### Do while loop runs at least once.

### Underflow
    When the magnitude of the operation is too small or is out of range of the specified data  type usually when you try to subtract a super small number from a smaller number that it is out of range of the data type which can handle.

### Version Control:
    A system that tracks changes to a file/set of files over time for us to keep record of specific versions later on

### While loop 
    checks a condtion if it is met and keeps on executing until it evaluates to false and is one of the infinite loops.

### Integer Overflow
    When an arithmetic operation takes place and the value we try to compute is either too small or too big for the specified
    datatype we try to perform the operation on

### File I/O
    We use File I/O in programming to work with files such as read a file, write to a file. The I stands for Input which we write to a file it is input. When we output contents from a file that is output.

### String Functions And Formatting
    String functions are methods we perform on a string data type. Formatting is used so that when we try to perform a function on a string it doesn't raise an error or we perform formatting on a string to display a nice result for good programming practice.
