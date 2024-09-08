**C# Notes**

**Value types**
Store actual data directly. Typically stored in the stack (RAM). 
Include int, float, long, double, char, bool, decimal, struct, enum.
Can be stored in heap if part of reference type.

**Reference Type**
Reference type is variable which instead of storeing the value in memory directly stores the memory location of actual data.
Reference type are string, array, class etc

**Implicit Conversion**
When you dont want to manually convert value from one data type to another it called as implicit conversion.
ex 
int i = 12;
double d = i;

**Explicit Conversion**
When you write code specifically to convert data type from one type to another then it is called as explicit conversion
ex 
int i = 12;
string strnum = i.ToString();

**Parse vs Convert**
-------------------------------------------------------------------------------------------------------------------------------
Parse                                                        | Convert                                                         |
-------------------------------------------------------------------------------------------------------------------------------
Works with only string values that are in compatible format  | Can work with any value we can able to convert it into any type.|
-------------------------------------------------------------------------------------------------------------------------------

**Reserverd Characters of C#**
These reserved characters include:

Braces ({ }) - Used to define the scope or block of code, such as methods, loops, conditionals, and class definitions.
Parentheses (( )) - Used for method calls and declarations, controlling order of operations in expressions, and surrounding conditions in control structures like if, for, while, etc.
Square Brackets ([ ]) - Used for array type declarations and accessing array elements. Also used in attributes.
Semicolon (;) - Used to terminate statements.
Colon (:) - Used in conditional (ternary) operator expressions, in the context of case statements within a switch, and to denote a base class or interfaces in class declarations.
Comma (,) - Used to separate items in a list, such as parameters in method declarations, or variables in declarations.
Period (.) - Used to access members of a class or namespace, such as methods or properties.
Question Mark (?) - Used in nullable type declarations and the null-conditional operators. Also part of the conditional (ternary) operator.
Plus (+) - Used as an arithmetic operator and to concatenate strings. Also used to denote unary plus or to define overloaded operators.
Minus (`-`) - Used as an arithmetic operator, to indicate a negative number, or to define overloaded operators.
Asterisk (`*`) - Used as an arithmetic operator for multiplication, to denote pointer types, or to define overloaded operators.
Slash (/) - Used as an arithmetic operator for division. Also starts comments (// for single-line comments, /* */ for multi-line comments).
Percentage (%) - Used as the modulus operator.
Ampersand (&) - Used for the 'address-of' operator in unsafe code, logical AND, and bitwise AND. Also used in method signatures to indicate a reference parameter.
Pipe (|) - Used for logical OR and bitwise OR.
Caret (^) - Used for bitwise XOR.
Exclamation Mark (!) - Used to denote logical negation.
Tilde (~) - Used for bitwise NOT and to define destructor methods in classes.
*Angle Brackets (`(< and >)** - Used in generic type definitions and methods, as well as for less than and greater than comparisons.
Equals (=) - Used for assignment and to test equality when paired with another equals sign (i.e., ==). Also used in lambda expressions (=>).
At Sign (@) - Used as a prefix to indicate a verbatim string literal, where escape sequences are ignored, or to use keywords as identifiers.
Dollar Sign ($) - Used to denote string interpolation, allowing variables to be embedded directly within string literals.
Backslash (\\) - Used as an escape character in string literals. For example, \\n for a new line or \\t for a tab.
Hash (#) - Used in preprocessor directives, such as #define, #if, #else, #endif, #region, and #endregion.

**Logincal Operators**
And, OR used to create complex logical conditions that evalueate either true or false.
AND combines two conditions and check if both are true
OR combines two evalute two and check either of it should be true


**Comparative Operators**
Compare values using operators like equal to . greater than and less than.


