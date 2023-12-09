# Task 2

User input can take many forms, from strings to numerical values. In this task, you will learn how to make use of numerical input from the user, similar to Task1.

## Readings: Useful JavaScript methods

### ParseInt() and Prompts

As practice, let's consider how we could create a program that does these things:

1. Asks the user for a number with a pop-up prompt screen.
1. Asks the user for a second number with a pop-up prompt screen.
1. Adds the first number and second number together to produce a result.
1. Displays the result to the user in an alert window.

Think about how you would solve the problem for a minute.
Try to write the code yourself. Did your code solve the problem?
Most likely, you were close, but when you used "+" JavaScript performed string concatenation instead of number addition.
It did that because the `window.prompt()` method returns strings even when the strings actually look like numbers.
What you need to know is a method called `parseInt()` that will convert a string (*str*) into a number. See the answer below:

<pre>var number1 = window.prompt("Enter a number:");
var number2 = window.prompt("Enter a number:");
var result = parseInt(number1)+parseInt(number2);
window.alert(number1+"+"+number2+"="+result);
</pre>

A screenshot is below.

<img src="images/parseInt_solution.png">

## Task 2.1 - Numerical Input

Here's what you need to do for this task:

- Similarly to Task1, you will do everything in <a href="task2/task2.html">task2.html</a>

- Add a comment with your full name and student number.

- Ask the user for their name with a pop-up prompt screen.

<img src="images/p1.png">

- Ask the user for their birth year with a pop-up prompt screen.

<img src="images/p2.png">

## Task 2.2 - Using numerical input

There are multiple ways you can use numerical input through JavaScript. For this task, you will need to use the getFullYear() method.

The getFullYear() method allows you to get the full year of a date of your choosing (this can be the current year or another year). In order to current year, you will need to the following block of code:

```
var d = new Date();
var year = d.getFullYear();
```

Here's what you need to do:

-  Determine the age of the user given the user input and the code above.

## Task 2.3 - Printing Input

Here's what you need to do for this task:

- Write the name of user and their age into the document.

Here's roughly what we are expecting of you:

<img src="images/task3_output.png"/>
