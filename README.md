# Calculator
## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
### General Info
***
  1This is a calculator appication where the user can do operations, save them in a text file and retrive them later.

The programm begins asking the user to choose between do operations or read them from a text file.

If choose operations:
* Asks the user for a number 
* Ask for the operator
* Ask for the second number
* Display the result

If choose read the operations:
* Ask for the name of the text file
* If correct, displays all the operations


The application is programmed for handle the exeptions and avoid the program to crash.

The following Exeptions and handles:
* ValueError (if insert a value that isn't a number)
* ZeroDivisionError (if a number is divide by 0)
* OverflowError (if the result is loo large)
* SyntaxError (if entered an invalid operator)
* FileNotFoundError (if enterd the incorrect file name)

### Technologies
***
The technologies used for this project are:
* [Python 3.10.9](https://www.python.org/downloads/release/python-3109/)

### Installation
***
A little intro about the installation. 
```
$ git clone https://github.com/lasagna92/Calculator.git
$ cd ../path/to/the/file
$ npm install
$ npm start
```
