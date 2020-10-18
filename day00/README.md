# Day00 - Basic 1
![](https://img.shields.io/badge/FirstDay-Basic1-orange)

In the first day we will lear about the very basic in python. Ex: Basic setup, variables, types, functions, ..

Table of contends

## Exercise 01

Makes a program that reverses the order of a string and the case of its words.
If it has more than one argument, it will merge them into a single string and separate each arg by a ' ' (space char).

```shell
> python exec.py "Hello World!" | cat -e
!DLROw OLLEh$
> python exec.py "Hello" "my Friend" | cat -e
DNEIRf YM OLLEh$
> python exec.py
>
```

## Exercise 02

Makes a program that checks if a number is odd, even or zero.
The program will accept only one parameter, an integer.

```shell
> python whois.py 12
I'm Even.
> python whois.py 3
I'm Odd.
> python whois.py
> python whois.py 0
I'm Zero.
> python whois.py Hello
ERROR
> python whois.py 12 3
ERROR
```

## Exercise 03

Creates a function called ```text_analyzer``` that displays the sums of upper-case characters, lower-case characters, punctuation characters and spaces in a given text.

```text_analyzer``` will take only one parameter: the text to analyze. Handle the case where the text is empty (maybe by setting a default value). If there is no text passed to the function, the user is prompted to give one.

Python console:

```
> python
>>> from count import text_analyzer
>>> text_analyzer("Python 2.0, released 2000, introduced 
features like List comprehensions and a garbage collection
system capable of collecting reference cycles.")
The text contains 143 characters:
- 2 upper letters
- 113 lower letters
- 4 punctuation marks
- 18 spaces
>>> text_analyzer("Python is an interpreted, high-level,
general-purpose programming language. Created by Guido van
Rossum and first released in 1991, Python's design philosophy
emphasizes code readability with its notable use of significant
whitespace.")
The text contains 234 characters:
- 5 upper letters
- 187 lower letters
- 8 punctuation marks
- 30 spaces
>>> text_analyzer()
What is the text to analyse?
>> Python is an interpreted, high-level, general-purpose
programming language. Created by Guido van Rossum and first
released in 1991, Python's design philosophy emphasizes code
readability with its notable use of significant whitespace.
The text contains 234 characters:
- 5 upper letters
- 187 lower letters
- 8 punctuation marks
- 30 spaces
```

## Exercise 04

Makes a program that prints the results of the four elementary mathematical operations of arithmetic (addition, subtraction, multiplication, division) and the modulo operation. This should be accomplished by writing a function that takes 2 numbers as parameters and returns 5 values, as formatted in the console output below.

```
> python operations.py 10 3
Sum:         13
Difference:  7
Product:     30
Quotient:    3.3333333333333335
Remainder:   1
>
> python operations.py 42 10
Sum:         52
Difference:  32
Product:     420
Quotient:    4.2
Remainder:   2
>
> python operations.py 1 0
Sum:         1
Difference:  1
Product:     0
Quotient:    ERROR (div by zero)
Remainder:   ERROR (modulo by zero)
>
> python operations.py
Usage: python operations.py <number1> <number2>
Example:
    python operations.py 10 3
>
> python operations.py 12 10 5
InputError: too many arguments

Usage: python operations.py <number1> <number2>
Example:
    python operations.py 10 3
>
> python operations.py "one" "two"
InputError: only numbers

Usage: python operations.py <number1> <number2>
Example:
    python operations.py 10 3
>
> python operations.py "512" "63.1"
InputError: only numbers

Usage: python operations.py <number1> <number2>
Example:
    python operations.py 10 3
```

## Exercise 05

## Exercise 06

It is time to discover Python dictionaries. Dictionaries are collections that contain mappings of unique keys to values.
Hint: check what is a nested dictionary in Python.

First, you will have to create a cookbook dictionary called ```cookbook```.

Cookbook will store 3 recipes:
- sandwich
- cake
- salad

Each recipe will store 3 values:

- ingredients: a list of ingredients
- meal: type of meal
- prep_time: preparation time in minutes

Sandwich's ingredients are ham, bread, cheese and tomatoes. It is a lunch and it takes 10 minutes of preparation.
Cake's ingredients are flour, sugar and eggs. It is a dessert and it takes 60 minutes of preparation.
Salad's ingredients are avocado, arugula, tomatoes and spinach. It is a lunch and it takes 15 minutes of preparation.

1. Get to know dictionaries. In the first place, try to print only the keys of the dictionary. Then only the values. And to conclude, all the items.

2. Write a function to print a recipe from cookbook. The function parameter will be: name of the recipe.

3. Write a function to delete a recipe from the dictionary. The function parameter will be: name of the recipe.

4. Write a function to add a new recipe to cookbook with its ingredients, its meal type and its preparation time. The function parameters will be: name of recipe, ingredients, meal and prep_time.

5.  Write a function to print all recipe names from cookbook. Think about formatting the output.

6. Last but not least, make a program using the four functions you just created. The program will prompt the user to make a choice between printing the cookbook, printing only one recipe, adding a recipe, deleting a recipe or quitting the cookbook.

```
> python recipe.py
Please select an option by typing the corresponding number:
1: Add a recipe
2: Delete a recipe
3: Print a recipe
4: Print the cookbook
5: Quit
>> 3
Please enter the recipe's name to get its details:
>> cake
Recipe for cake:
Ingredients list: ['flour', 'sugar', 'eggs']
To be eaten for dessert.
Takes 60 minutes of cooking.
```

## Exercise 07

Using list comprehensions, you will have to make a program that removes all the words in a string that are shorter than or equal to n letters, and returns the filtered list with no punctuation. The program will accept only two parameters: a string, and an integer n.

```shell
> python filterwords.py "Hello, my friend" 3
['Hello', 'friend']
> python filterwords.py "A robot must protect its own existence as long as such protection
,! does not conflict with the First or Second Law" 6
['protect', 'existence', 'protection', 'conflict']
> python filterwords.py Hello World
ERROR
> python filterwords.py 300 3
ERROR
```

## Exercise 08

You will have to make a function which encodes strings into Morse code. The input will accept all alphanumeric characters.

```

```

## Exercise 09

## Exercise 10