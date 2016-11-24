# Ruby-Programs

## Problem 1

Write a class that - applies the following rules:

* If a character has the same character to its left and right, it should be replaced with that other character (i.e. AWA becomes AAA) unless the surrounding character is a space
* Any sequence of six characters should be replaced with a single character, i.e. AAAAAA becomes A
* Any instance of the exclamation mark (!) character causes the string to be reversed, and the exclamation mark character removed

When you're done, try running it on the following string and see what result you get.

!YTIRCO!IQIIQIDEMGMMIM FO YMJMMSM!RA !EGEEJEHT ROEOOSOF PAEJEEBEL TN!AIKIITIG ENVNNMNO ,GQGGCGN!ILEKIZIISIRT A RJRRDROF PETOTTJTS LLZLLEL!AMSXSSMS ENODOOSO

* ...

## Problem 2

Write a class that in its constructor takes as one argument an sequence of integers (we'll call these the operands), and as another argument another integer (we'll call this the desired result). Your class should provide a method guess that takes an integer (guesses). When guess is called, your class should attempt to output string representations of equations, their result, and the difference between that result and the desired result guesses times. Finally, the class should output the number of guesses and what the best guess was.

e.g.

> equation_guesser = EquationGuesser.new([1, 2, 3, 4], 24)
> equation_guesser.guesses(3)
1 + 2 + 3 + 4 = 10 (-14)
1 * 2 * 3 * 4 = 24 (0)
Guesses: 2 Best Guess: 1 * 2 * 3 * 4 = 24 (0)
If the equation is exactly equal to the desired result, the program should exit. For the sake of this exercise, you only need consider positive integers (i.e. use integer division). Your equations should honour standard operator precedence (e.g. multiplication before addition) and do not need to consider bracketed subexpressions (e.g. (1 + 2) * (3 + 4)).

For extra points:

* make it so your guess method can process up to 10 operands and 1000 guesses without taking more than 5 seconds
* do at least one thing that reduces the average number of guesses your class needs to make for each call to guess before it is able to achieve the desired result.

## Problem 3

Here is the challenge.

* Take a list of integers on standard input, one per line, and return them in reverse order on standard output, or;
* Take a string on standard input and return the string reversed on standard output.
Conditions:

* You must do this in a language that you have not programmed in before.
* You must not use a library that provides a reverse method or function.

* ...
