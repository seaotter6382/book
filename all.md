# How to use Python3 for Beginners

## Version 0.1.2
## By: Hugh Quigley

\newpage

# Table of Contents

## How to install Python3 ....................... 3

## Chapter 0, The Python Shell ................. 4

## Chapter 1, The Hello world of Python ........ 5

## Printing in Python ........................... 5

## Making Variables ............................. 5

## Printing Variables ............................ 6

## Making String Variables ...................... 6

## Chapter 2, Functions and Classes  ............ 8

## Making Functions ............................. 8

## Making Inputs into Functions ................. 8

## Expanding on the Functions Inputs ............ 10

## Making Classes ............................... 11



\newpage

## Things in this book

You might notice things in this book as "extensions". These are like a chalenge that you can do. With other tips and ideas from the book, you should try and reach the goal of making the extension.

Also, anything in the book that is `like this font`, that usally means that it is a `code word` or a `code block`.

Anyway, have fun reading this book. 

## How to install Python3

### Mac

For Mac, you just go to [Python.org](https://www.Python.org/downloads), and then download python. Once it is downloaded, (you may have to enter your admin password) you can lanch it using the lanchpad on the bottom left of your mac screen. Once lanched you can enter any command through the terminal prompt, or create a new file.

### Windows 
For Windows, it is around the same thing as mac, go to [Python.org](https://www.Python.org/downloads), and then click download python. Then, to run python, just open the IDLE app and then python should launch.

### Linux
Installing python for Linux is really easy, just open up terminal and then do 

\hrulefill

`sudo apt install python3`

\hrulefill

Then, to launch python, you just do `python3` into the terminal. To edit any file, you can use any Unix text editor (Vim, Vi, etc..). And then to run any python file, you just do

\hrulefill

`python3 (path to file)`

\hrulefill

\newpage

# Chapter 0
## The Python Shell

The Python Shell is sort of like the basic prompt of python. It is not a file, it is just a prompt. Think of the prompt sort of like searching things up on google. You enter the thing you want, and then it gives you something in return.

The Python Shell is sort of like that.

### Launching the Shell on Mac

To lanch the shell on Mac, just follow these steps

1. Open the python IDLE app (you can open it inside of your applications inside of the finder, or just find it in the lanchpad)
2. Once it is open it automatically opens the Python Shell. You can do your stuff here.

### Lanching the Shell on Windows

To lanch the shell on Windows, follow these steps

1. Click your search button on the bottom of your screen
2. Search for 'IDLE'
3. Once it shows up, click on it. The Python Shell should launch.

### Lanching the Shell on Linux

To lanch the shell on Linux, follow these steps

1. Once you have it installed enter `python3` into the terminal
2. The prompt should look like this:

\hrulefill

`Python 3.11.2 (main, Mar 13 2023, 12:18:29) [GCC 12.2.0] on linux`

`Type "help", "copyright", "credits" or "license" for more information.`

`>>>`

\hrulefill

3. Once you see the `>>>` you know you are in the python terminal.

A lot of the things in this book are made for a new file, not part of the Python Shell. To create a new file from the python shell, you can just click the `File-New` (or something like that), and then you can enter the code in the window that pops up.

To run the window/file, you just press `Run-Run` (or something like that). The program should lanuch. You can also put in basic commands into the python shell, such as `print()` or making variables, etc..


\newpage

# Chapter 1
## The Hello World of Python

In this chapter, I will talk about printing things, and making variables.

Things disscussed in this chapter:

1. Baisc Printing
2. Making Variables
3. Printing Variables

## Printing in Python

To print in Python, you just enter print, and then open parenthesis, and then open quotation, and then your word, close quotation and close parenthesis. Here is a example of printing something in python.

*helloworld.py, example 1.0*

```python
print("Hello World!")
```

The output of that code will be:

\hrulefill

`Hello World!`

\hrulefill

If you want to print something else, you can just replace the 'Hello world' with something else. A example of that would be something like this:

*helloworld2.py, example 1.5*

```python
print("Hamburgers are good!")
```

The output of this would be:

\hrulefill

`Hamburgers are good!`

\hrulefill

## Making Variables

In this sub-chapter, I will talk about making Variables in python. Making variables is acaully really easy, you just need the name of it and the value. Here is a example of doing just that.

*Variable1.py, example 2.0*

```python
Test = 3
```

Output:

\hrulefill

(Nothing)

\hrulefill

What this does, it now if you refence 'Test' then it will output 3 (becuase the value of 'Test' is 3). If you want to change the value of 'Test' you can just change the Value from 3 to something else.

### Printing Variables

To print a variable, it is just really easy, it is just like a print statement but instead of open quotation marks it is just your variable name. Here is a example of making a variable and then printing it.

*Variable2.py, example 2.5*

```py
Test = 3
print(Test)
```

Output:

\hrulefill

`3`

\hrulefill

### Making String Variables

To make a String Variable, you can just replace the number (3) with a open quotation marks and then your word, and then close quotation marks. Here is a example of making just that.

*StringVariable.py, example 3.0*

```py
Test = "hello!"
print(Test)
```

Output:

\hrulefill

`hello!`

\hrulefill

If you want to print a variable and a word, you can do this:

*StringVariable2.py, example 3.5*

```py
Test = "Hello"
print(Test + " World!")
```

Output:

\hrulefill

`Hello World!`

\hrulefill

Here is a step by step guide of how this works.

1. It first creates a varaible (Test) and the value is "Hello"
2. Then, it starts to print a variable like you normaly do, but after the varaible you do the `+` to seperate varaible and string 
3. After the `+`, you do open quotation and then a space, to make a space inbetween the variable and the string (without it there would be no space)
4. Finally, you close the string (with a quotation mark) and then a close parentheses

To conclude this chapter, you can use your variable name and then the value to make a varaible, and then to print it, you just do it inside of the print statement.

\newpage

# Chapter 2
## Functions and Classes

In this chapter, you will learn about functions, and how to use them. Also, you will learn about classes, and how to use them.

### Making Functions

Functions are basically like a group of code, that you can call anytime. In the function, you can do anything, and then you can call it anytime.

Here is a example of making a function.

```py
def hello():
    print("Hello world!")
```

Output:

\hrulefill

(Nothing)

\hrulefill

This will have no output, but this will create the function `hello` and then in the function, it will print `Hello world!`.

To call a function and to use it, you can just say the function name (in this case, the function name is `hello`).

Here is a example of making a function, and then calling a function.

```py
def hello():
    print("Hello world!")

hello()
```

Output:

\hrulefill

`Hello world!`

\hrulefill

### Making inputs into functions

Inputs into functions are sort of like configring the function. For example, you could make it print a number that you put into the function. 

Here is a example of making a input into a function

```py
def function(number):
    print(number)

function(4)
```

Output:

\hrulefill

`4`

\hrulefill

This will output the number 4, becuase you inputed the number 4 into the function, and then in the function code it refencses the number that you put into it, and in this case it prints the number.

If you try and replace the number with the word `hello`, you will get a error.

Code:

```py
def function(number):
    print(number)

function(hello)
```

Output:

\hrulefill

`Traceback (most recent call last):`

`File "<main.py", line 3, in <module>`

`NameError: name 'hello' is not defined`

\hrulefill

This error shows up becuase you entered a word without using a quotation mark, so python does not know that it is a string, it thinks you are trying to refence a variable but the variable `hello` is not defined.

To fix this error, you can just add quotation marks to the word hello.

```py
def function(number):
    print(number)

function("hello")
```

Output:

\hrulefill

`hello`

\hrulefill

## Expanding on the Functions' inputs

You can have more than one function input, up to a lot. Here is another example of using 2 function input.

```py
def function(number1, number2):
    print(number1)
    print(number2)

function(4, 2)
```

Output:

\hrulefill

`4`

`2`

\hrulefill

This function refences the two inputs into the function, and then prints both of them. You can change the numbers in the line `function(4, 2)` to diffrent numbers or add quotations over the numbers and then enter any word (once you have quotations around the number).

If you don't enter any inputs to a function that has inputs, you will get this error:

Code:

```py
def function(number1, number2):
    print(number1)
    print(number2)

function()
```

Result:

\hrulefill

`Traceback (most recent call last):`

`File "<main.py>", line 5, in <module>`

`TypeError: function() missing 2 required positional arguments: 'number1' and 'number2'`

\hrulefill

This says that you always need a input to a function when the function requires a variable.

\newpage

## Returning with Functions

With a function, you can make a `return` statement. This is like the function doing its code, and then outputting it. All of the examples I have shown so far does not use any returns, the functions prints the things inside of the functions.

A example of a return function will sort of be a caculator. You put a number in, and then it returns the number; changed.

Here is a example of using a return statement in a function

```py
def add(number1, number2):
    result = number1 + number2
    return result
```

This is a function that justs gets 2 numbers, adds then together and then return the result of those numbers. To use the result of those numbers, you can put the function in a print statement, or make a variable the function. Here is a example of both.

```py
def add(number1, number2):
    result = number1 + number2
    return result

burger = add(3, 4)
print(burger)
print(add(4, 5))
```

Output:

\hrulefill

7

9

\hrulefill

**Extension** Make a function, that instead of adding it, it subtracts it.

## Making Classes

Classes are sort of like one big variable with a lot of diffrent sub variables. Here is a example of making a class in python.

```py
class hello:
    title = "Hello"
    burger = "Burger!"
```

In this code, it will create a class `hello`, and then it will make some sub variables called `title` and `burger`. The value for `title` is "Hello", while the value for `burger` is "Burger!"

If you want to print any of these values, you can just first do the class name, (in this case it is `hello`) and then your sub variable inside the class (if I want to print the sub variable title, I would say `print(hello.title)`).

Here is a example of creating a class and then printing the values

```py
class hello:
    title = "Hello"
    burger = "Burger!"

print(hello.title)
print(hello.burger)
```

Output:

\hrulefill

`Hello`

`Burger!`

\hrulefill

This works becuase in the class, it creates some variables, so then to refrence the variables you have to first do the class name, and then the variable in the class you want to reference.

## Review; Functions and Classes

Functions are a gruop of code, and Classes are like a big variable, and it has siffrent sub variables inside of it.

Some more examples of functions and classes.

```py
def word(word):
    print(word)

class hello():
    title = "cool"
    number = 32

word("burger")
print(hello.title)
print(hello.number)
```

Output:

\hrulefill

`burger`

`cool`

`32`

\hrulefill

**Extension**: Make a class, and then inside of the class make 2 variables. Then, make a functions that finds thoses two variables and then returns the value of thoses two variables combined.

\newpage

# Chapter 3
## Inputs and If Statements

In this chapter, you will learn about how to make inputs into your code, and how to make if statements.

## Inputs

To make any input in your code, you can use the `input()` statement when making a variable. Here is a example of making a input into your code:

```py
word = input()
print(word)
```

Output:

\hrulefill

This depends on what you inputted into the script

\hrulefill

When you run this script, you might notice that the script sort of paused, like waiting for a input. To stop this pause, you just input any word (for example `cat`, `dog`, `hamburger`, etc..) and then it should print out your word.

If you want to make it instead of just printing back your word, it will print some text that goes with it, you can edit the script like so:

```py
word = input()
print("Your word is " + word)
```

Output:

\hrulefill

`Your word is [your word]`

\hrulefill

But still, it feels a bit weird running the code, if you don't know what the code does, then you would wonder why the program just stopped so suddenly. To fix this, you could add a print statement that tells you to enter a word.

```py
print("Enter a word")
word = input()
print("Your word is " + word)
```

Output:

\hrulefill

`Enter a word`

`Your word is [your word]`

\hrulefill

To summerize, this program will first print `Enter a word`, and then it will get the user's input (as a text), and then it will print the input. Next, you will learn how to make if statements and then make a final program that uses the inputs and a if statement.

## If Statements

If statements are sort of like checking if something is equal to a value, if not then the following code will not run. A real-life example of a if statement would be something like this; If I have enough money to buy this, then I would buy it. If I don't have enough money, then I won't buy it.

A if statement is sort of like that. It checks if the if statement's needs are met, and if it is then it will run a bit of code, if is it not met, then it will just skip the if statement. Here is a example of making a python if statement.

```py
Burger = 4
if Burger == 4:
    print("The burger value is 4!")
```

Output:

\hrulefill

`The burger value is 4!`

\hrulefill

Here are the important steps you should remember when making a if statement:

• You MUST always put the `==` sign, not the `=` sign.

• You MUST always put the `if` at the start of every if statement.

• To end the first line of a if statement, you use the `:` character.

If you follow these rules, you should be able to make a if statement.

But, if you are wondering, yes, you can do any string (text), any int (number), and any bool (true or false).

Here is a example of using a input (as discused earlier), and then making a if statement with that.

```py
print("Enter a word")
word = input()
if word == "burger":
    print("The word was burger!")
else:
    print("Wrong word!")
```

Output:

\hrulefill

(if the word was "burger")

    The word was burger!

(if the word was something else)

    Wrong word!

\hrulefill

In this code, I interduced a new command; `else:`. This is basically a statement like the if command, but it is like a else if command. If you place it after a if command, it will run if the if command above it is false. But it will not run if the if command is true.

You can do a lot of things with inputs, like you could put it all lower case by using `lower()`, or you can make it all upper case by using `upper()`. Here is a example of using that:

```py
print("Enter a word")
word = input()
print("Your word is " + word)
wordlower = word.lower()
print("Your word in lowercase is " + wordlower)
wordupper = word.upper()
print("Your word in caps is " + wordupper)
```

This will print your word back as normal, all lower case and all upper case.

**Extension** Make a function that when you put a variable into it, it will return it with the variable all upper case

## Inputs and functions

Say if you really wanna make a full caculator in python. You could always use the python shell, but say you really wanted to make a caculator. How would you do it? Think about what this book has said so far.
You could make a function, with 1 input, and if the input is 1, make it a add caculator. If the input is 2, make it a subtraction caculator, etc..
Here is a example of just that:

## Project: Python Calculator

```py
1. def calculator(number):
2.     if number == 1:
3.         print("Enter your first number")
4.         word1 = input()
5.         print("Enter your second number")
6.         word2 = input()
7.         word3 = word1 + word2
8.         print(word1 + " + " + word2 + " = " + word3)
9.     if number == 2:
10.        print("Enter your first number")
11.        word1 = input()
12.        print("Enter your second number")
13.        word2 = input()
14.        word3 = word1 - word2
15.        print(word1 + " - " + word2 + " = " + word3)
16.    if number == 3:
17.        print("Enter your first number")
18.        word1 = input()
19.        print("Enter your second number")
20.        word2 = input()
21.        word3 = word1 / word2
22.        print(word1 + " / " + word2 + " = " + word3)
23.    if number == 4:
24.        print("Enter your first number")
25.        word1 = input()
26.        print("Enter your second number")
27.        word2 = input()
28.        word3 = word1 * word2
29.        print(word1 + " * " + word2 + " = " + word3)
30.
31. calculator(1)
32. calculator(2)
33. calculator(3)
34. calculator(4)
```

Here is a breakdown of how this works.

### Creating the function

```py
1. def calculator(number):
```

This line creates the function, with one function input; `number`. This is used for determining if the calculator adds, subtracts, divides or multiplys.

### Making the Add Part

```py
2. if number == 1:
3.     print("Enter your first number")
4.     word1 = input()
5.     print("Enter your second number")
6.     word2 = input()
7.     word3 = word1 + word2
8.     print(word1 + " + " + word2 + " = " + word3)
```

On line 2, it checks if the functions input `number` is 1. If the number is 1, it will continue with the if statement. If the number is not 1, then it will pass the if statement.
So, if the number is 1, it will print "Enter your first number". This is usefull because the user would not know what to do if the python program just stopped.
Then, it gets the user's input by 


