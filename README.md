##Bitwise Operators in C Programming

In the arithmetic-logic unit (which is within the CPU), mathematical operations like: addition, subtraction, multiplication and division are done in bit-level. To perform bit-level operations in C programming, bitwise operators are used.

##Bitwise AND Operator &
The output of bitwise AND is 1 if the corresponding bits of two operands is 1. If either bit of an operand is 0, the result of corresponding bit is evaluated to 0.

In C Programming, the bitwise AND operator is denoted by &.

Let us suppose the bitwise AND operation of two integers 12 and 25.
'''
12 = 00001100 (In Binary)
25 = 00011001 (In Binary)

Bit Operation of 12 and 25
  00001100
& 00011001
  ________
  00001000  = 8 (In decimal)
  '''
  ##Bitwise OR Operator |
The output of bitwise OR is 1 if at least one corresponding bit of two operands is 1. In C Programming, bitwise OR operator is denoted by |.
let us suppose the bitwise OR operation 
'''
12 = 00001100 (In Binary)
25 = 00011001 (In Binary)

Bitwise OR Operation of 12 and 25
  00001100
| 00011001
  ________
  00011101  = 29 (In decimal)
  '''
  ## Bitwise XOR (exclusive OR) Operator ^
  The result of bitwise XOR operator is 1 if the corresponding bits of two operands are opposite. It is denoted by ^.
let us suppose the bitwise XOR operation
'''
12 = 00001100 (In Binary)
25 = 00011001 (In Binary)

Bitwise XOR Operation of 12 and 25
  00001100
^ 00011001
  ________
  00010101  = 21 (In decimal)
  '''

**Find some more applications here :**</br>
https://www.programiz.com/c-programming/bitwise-operators



