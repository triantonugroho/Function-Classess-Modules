# **Function**
A function in python is a collection of commands or lines of code that are grouped into a single unit so that they can be called or used many times. A function can accept parameters, can return a value, and can be called independently many times.
- a function is defined with the def keyword followed by the name of the function and its parameters in bracket(). the code block in each function starts with a colon (:) and is indented. the function stops when there is a return (expression) statement that returns (expression) to the caller
- optionally, you can add a docstring (string documentation describing the context of the function). You can also make the function return no output with return none
- by default, python will position each parameter according to the order in which it was registered at the time it was defined and must be called in that order. But you can also enter it in an unordered way by writing parameters and arguments 
- the return (expression) statement will make program execution exit the current function

## Function-Argument and parameter
A function in python is a collection of commands or lines of code that are grouped into a single unit so that they can be called or used many times.

A function can accept parameters, can return a value, and can be called independently many times. A function can also accept parameters or arguments. It is a value/variable that is thrown into a function for further processing.
There are several possible arrangement/order of function parameters:

1. positional or keyword : is to write argument as keyword

2. positional only : specifies that the argument can only be placed in a certain position.

3. keyword only : specifies that certain arguments must be supplied in the form of keyword arguments.

4. var-position and var-keyword : you specify that there are several position arguments and there are several keyword arguments to be processed. var-position is marked with a start (* = iterable) and var-keyword is marked with a start (** = dictionary).
Lambda expressions in Python are expressions for creating functions. by using a lambda we can create a function without a name or also known as an anonymous function. Lambda can have more than one argument or parameter, but can only have one expression or body. Since lambda is an anonymous function, it is free to use any name. In other words, lambda functions can be stored in any variable. This of course cannot be done by a function created with def.

# **Classes**
Classes provide a means of bundling data and functionality together. Creating a new class creates a new type of object, allowing new instances of that type to be made. Each class instance can have attributes attached to it for maintaining its state. Class instances can also have methods (defined by its class) for modifying its state.
## Double Underscore init (\_\_init\_\_)
Use the \_\_init\_\_() function to assign values to object properties, or other operations that are necessary to do when the object is being created
## Object Method
Class object could be used to access different attributes
## Class Method
A class method takes **cls** as the first parameter 
## Static Method
Static method needs no specific parameters

# **Management txt file**
## txt file - write 
write() is used to write txt file in python without using notepad.

## txt file - open
upload() is used to open txt file in python from existing folder location.

## txt file - read
* read() is used to read all contents of existing txt file in python.
* readline() is used to read the first line of existing txt file in python.
* readlines() is used to read the spesific line of existing txt file in python.

## txt file - close
close() is used to close txt file in python (delete temporary memory).

# **Module** 
## **pydoc**
The pydoc module automatically generates documentation from Python modules.

## **io**
The io module provides Python’s main facilities for dealing with various types of I/O


## **os**
### os.path.isfile()
os.path.isfile() method in Python is used to check whether the specified path is an existing regular file or not.

### delete file
All you need to do to remove a file is call os.remove() with the appropriate filename and path (Python defaults to the current directory, so you don’t need to specify a path if the file you want to remove is in the default directory).

### create directory
The OS module in Python provides functions for interacting with the operating system. OS comes under Python’s standard utility modules. This module provides a portable way of using operating system-dependent functionality.

## **unit test** 
### test case
A test case is the individual unit of testing. It checks for a specific response to a particular set of inputs. unittest provides a base class, TestCase, which may be used to create new test cases.

## **random**
### randint
randint() is an inbuilt function of the random module in Python. The random module gives access to various useful functions and one of them being able to generate random numbers, which is randint().

## **datetime**
A date in Python is not a data type of its own, but we can import a module named ***datetime*** to work with dates as date objects
### Create Date Object
To create a date, we can use the ***datetime***() class (constructor) of the datetime module.
### strftime() Method
The datetime object has a method for formatting date objects into readable strings.

## **math**
This module provides access to the mathematical functions defined by the C standard.
* math.pi is used to calling the mathematical constants phi (3.141592...)
* math.ceil(x) is used to return the ceiling of x, the smallest integer greater than or equal to x.
* math.floor(x) is used to return the floor of x, the largest lest than or equal to x.

## **sys**
The sys module in Python provides various functions and variables that are used to manipulate different parts of the Python runtime environment. It allows operating on the interpreter as it provides access to the variables and functions that interact strongly with the interpreter. 
dalam modul sys ini terdapat Python Exception Handling. Exception adalah suatu keadaan saat penulisan syntax sudah benar, namun kesalahan terjadi karena syntax tidak bisa dijalankan, melainkan karena adanya kesalahan matematika, kesalahan nama function, library, dan lainnya tetapi proses tetap berjalan.
