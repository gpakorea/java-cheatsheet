# Java Cheatsheet
A quick-reference glossary-like collection of Java terms and commands.

```
public class ClassName {
  public static void main( String[] args ) {
    ...
  } // end main method
} // end class
```

- `// Endline comment`
- `/* Multi-line comment`
- `System.out.print();` Keeps cursor at the end of the line after printing
- `System.out.println();` Bumps cursor down to the following line after printing

Variable Types
- **int** = integers (whole numbers +/-)
- **double** = decimal (floating point numbers +/-)
- **String** (not a Primitive Type) = contained within quotation marks
- byte
- char
- float
- long
- boolean

Variable Names
- Begin with letter or underscore _ and can't contain punctuation except _
- camelCasingNamingConventions
- underscoring_naming_conventions
- final int CONSTANT

String Methods
- Concatenation = + (adding Strings together)
- `length()` = get number of characters in a String
- `substring(start,end)` = prints part of a String
- `toLowerCase()` = lowercases a String
- `toUpperCase()` = all capitals
- Escape sequences:
  - `\"` prints "
  - `\t` TAB
  - `\n` new line, line break, hard return
  - `\\` prints \

Operators
- = assignment
- + addition
- - subtraction
- * mulitplication
- / division
- % modulus (remainder)
- PEMDAS (parenthesis, exponents, multiplication, division, addition, subtraction)
- ++ increment (++x = increments BEFORE use; x++ increments AFTER use)
- -- decrement (--x = decrements BEFORE use; x-- decrements AFTER use)
- == comparison
- Compound operators: +=, -=, *=, /=, %=

Math Methods
- abs(x) = absolute value of x
- pow(x, y) = x to the power of y
- sqrt(x) = square root of x
- ceil(x) = returns next highest whole number
- floor(x) = returns next lowest whole number
- min(x, y) = returns minimun of x or y
- max(x, y) = returns maximum of x or y
- random() = returns random double between 0<=r<1
- round(x) = rounds to nearest whole number
- PI = returns 3.14159625...
- log(x) = log base e of x
- sin(x) = sin of angle x (in rad)
- cos(x) = cos of angle x (in rad)
- tan(x) = tan of angle x (in rad)
- asin(x) = arcsine of x in range -PI/2 to PI/2
- acos(x) = arccosine of x in range -PI/2 to PI/2
- atan(x) = arctan of x in range -PI/2 to PI/2
- toDegrees(angRad) = converts radians into degrees
- toRadians(angDeg) = converts degrees into radians
