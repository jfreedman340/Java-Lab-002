# Java-Lab-002

## Variables, Types and Operators

Be able to explain what variables are. Understand variable types, allowed names, and valid values.
Know how to create and use string, integer, floating-point, and boolean variables.

### Part 1 - PricelessScript.java - [MasterCard YouTube Ad](https://www.youtube.com/watch?v=Q_6stXKGuHo)

The lab template contains a program that prints the following:
```
2 tickets: $28.00
2 hotdogs, 2 popcorn, 2 sodas: $18.00
1 autographed baseball $45.00
real conversation with 11 year old son: priceless
true
```

Ignore the code that you don't fully recognize and concentrate on changing the variables to alter the MasterCard *Priceless* script to say:
```
3 tickets: $42.00
3 hotdogs, 3 popcorn, 3 sodas: $27.00
2 autographed baseball $90.00
watching the Giants win: priceless
false
```

### Part 2 - Interpretation
Take note of the various variables and their data types. Write a brief summary in this section of the README.md file listing the:
* Variable name
* Its data type
* and example values you can assign them.

Next give TWO example variable names and TWO example variable assignments that are *WRONG* and explain why.
* Hint: your IDE can help you discover these!

## Joseph Freedman's Summary
### The main variable types are strings, integers, floats, booleans, etc.
### Here are some examples from the code.

* // integer variable
* int people = 3;
* // 32 bit floating point variable
* float ticketPrice = 14.0f;  // 32 Bit, but it does exist!
* // double precision floating point variable
* double itemPrice = 9.0;    // Double precision
* // boolean variable
* boolean trueOrFalse = false;

1. Integers are whole numbers
2. Floats, or floating point numbers are not whole numbers such as 2.7 or 8.03.
3. Booleans are either True or False, 0 or 1.
4. A class is an object which can be assigned methods and variables.

### Examples of variables that are wrong.

1. If you wrote int xyz = 5.5; // That would be wrong because it's not a whole number.
2. If you wrote String xyz = Hello Yoda; // That would be wrong because it's not in quotes.
3. If you wrote boolean xyz = maybe; // That would be wrong because it's either true or false, not maybe.
 

### Part 3 - Bonus: Play around with Java String Format Specifiers.

Pick several of the Java format specifiers below and define variables of the correct type utilize *sout* and *String.format* to view the resulting formats.

![Format Specifiers](JavaStringFormatSpecifiers.png)

1. System.out.printf("%d %s%n", 3, "XYZ");
2. System.out.printf("%s %s%n", "Grade", "A");
3. System.out.printf("%s %s %s %d %s %d %s %d %s %d %s %d%n", "AAPL:", "Date 8/31/2010:", "Open", 123, "High", 130, "Low", 120, "Close", 125, "Volume", 5306736);

### These are some things I played around with.
They look like this
* 3 XYZ
* Grade A
* AAPL: Date 8/31/2010: Open 123 High 130 Low 120 Close 125 Volume 5306736


### Part 4 - Submission
* Commit your working code
* Push it to your Remote/origin branch (i.e. GitHub)
* Then issue a Pull request to the instructor branch
    * Make sure to save the Pull request URL and submit it for the lab.