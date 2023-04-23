Javascript Overview

1. High Level: Does not have to managae resources asking memory from computer.

2. Garbage-collected: A algrathm automatically clean the memery 

3. Interpreted (Just in time compiled): computer understands 0 and 1 (JS engine automatically converes human code to machine code with 0 and 1s)

4. Multi-paradigm: An approach and mindset of structuring code, which will direct your coding style and technique.
    > 1) Procedural programming
    > 2) Object-Oriented Programming (OOp)
    > 3) Functional Programming (FP)

5. Prototype based object oriented: Almost everything in JS is object except string, primitive values.

6. First Class Function: Functions are treated as variables. We can pass them into other functions and return them from functions.

7. Dynamic: No data type definitions. Types becomes known at run time. And data type of variable is automatically changed if a value of different type is assigned ie:
>> let x = 23
>> let y = 10
>> x = "text" 
The type of the variable can be changed easily when we reasign variables

8. Single threaded: JS can only do one thing at the time

>> Concurrency Model - JS engine handles multiple tasks happening at the same time

9. Non Blocking event loop: Takes ling running tasks, executes them in the background and puts them back inthe main thread once they are finished