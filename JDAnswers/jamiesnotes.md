# Jamie's Notes
These are my notes for the QR_Python Playbook track to help my learning and illustrate my understanding of the topics at hand.

## 1.1 First Steps

* What does it mean that Python is a strong, dynamically typed language?
**Strongly typed** means that you can't do unsafe operations on incompatible data types. E.g. it throws an error when you try to concatenate a string with a boolean value using the + symbol.
**Dynamically typed** means we don't need to declare our variable's datatypes, Python can figure them out implicitly. We can force Python to use certain datatypes by using inbuilt functions like float() or simply using "" to make something into a string.

* How do you run the Python interpreter?
Personally I run it in the command line of a Linux system, either as a VM on my windows machine or bare metal in the case of my personal laptop. Pyto is an interpreter I've used with varying degrees of success on iOS.

* How do you define a variable?
With the = symbol.

* What’s the difference between a variable name and a variable value?
The name is how you retrieve the value. If lordOfTheRings was a variable, all the words that make up the book would be its value

* What are Python’s built-in data types?
int, float, str, Boolean, lists, dictionary,tuples and sets

* What’s the difference between an integer and a floating-point number?
Integers must be whole numbers. This has an impact on memory usage (and therefore speed) so we should endeavour to use int whenever we don't actually need a float.

* What are Boolean values?
Truthy or less truthy

* What does the % operator do?
Modulo finds the remainder of 2 divisors

* What’s the difference between a list and a tuple?
Immutability

* What is a dictionary?
a list of key-value pairs

* Why should you use comments in your code?
To help you and your colleagues understand what you have done.
(also to be funny)

* What does help() do, and when is it useful?
help() runs python's help utility. Honestly I've never used it, but actually it seems quite useful! You can use it on built in functions if you are unsure what they do to get access to some documentation.

* What does dir() do, and when is it useful?
dir gives a list of names from an object/class/module, it is quite handy for figuring out what you can do with that thing

* What’s the difference between syntax errors and exceptions?
Syntax errors are simple mistakes of syntax... for instance forgetting the : in a conditional. Python can't continue running these. Exceptions are not unconditionally fatal but include most things that aren't syntax errors. E.g. if a function is expecting an int but gets a string that would throw an exception.

* What is pip?
The package manager for python libraries
