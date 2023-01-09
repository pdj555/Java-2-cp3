# Class Notes Week 5
## Down-Casting
- instanceof tells whether an instance is a member of a class
- code: if (s instanceof Triangle) { ...

## Casting and instanceof
In java one can inherite multiple interfaces but only one class

## Interfaces
- inplements for interfaces instead of extends for classes

## Upcasting
<img width="816" alt="Screen Shot 2022-09-19 at 11 55 17 AM" src="https://user-images.githubusercontent.com/102199778/191071709-d8d99884-b4d8-4f0a-8f31-637e8b8604ad.png">

## Implements vs Extends
- implement: impliments an interface
- extends: extends a class
  - inherits all elements from a class

## Challenges to building robust software
- user might enter incorrect data
- manipulating objects in incorrect ways
- operations ight fial
- system errors

## Techniques for highlighting errors
- System.out.println()
- return a value that indicates an error

## Exceptions
- method calls on unistantied objects
- creating 

### Syntax
try {}

catch() {}

finally {}

if you are going to fix the problem there is no reason to catch

## Throwing exceptions
https://www3.ntu.edu.sg/home/ehchua/programming/java/J5a_ExceptionAssert.html

<img width="780" alt="Screen Shot 2022-09-21 at 12 09 07 PM" src="https://user-images.githubusercontent.com/102199778/191568030-49c4f090-207d-42be-be6f-210dc79b3b98.png">

Code:

<img width="556" alt="Screen Shot 2022-09-21 at 12 03 53 PM" src="https://user-images.githubusercontent.com/102199778/191567088-477a5bd2-5d38-4b59-a33a-f56f1c37f54b.png">

<img width="384" alt="Screen Shot 2022-09-21 at 12 07 40 PM" src="https://user-images.githubusercontent.com/102199778/191567755-f0cfae74-fdab-4b84-85aa-b67cebfbab12.png">

https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/Object.html

<img width="648" alt="Screen Shot 2022-09-21 at 12 10 28 PM" src="https://user-images.githubusercontent.com/102199778/191568317-4fc35fec-a7b7-4da8-81ee-8edaa8746a59.png">

Put (Exception e) statements at the end of the exceptions; it is the least specific exception statement
