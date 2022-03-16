# Javascript Task - 1

## Level 1:


## Convert Age to Days
Create a function that takes the age in years and returns the age in days.	
### Example:
    calcAge(65) ➞ 23725
    calcAge(0) ➞ 0
    calcAge(20) ➞ 7300

## Return the  ***Remainder***   from Two Numbers	
There is a single operator in JavaScript, capable of providing the remainder of a division operation. Two numbers are passed as parameters. The first parameter divided by the second parameter will have a remainder, possibly zero. Return that value.
### Example:
    remainder(1, 3) ➞ 1
    remainder(3, 4) ➞ 3
    remainder(-9, 45) ➞ -9
    remainder(5, 5) ➞ 0
## Add up the Numbers from a Single Number
Create a function that takes a number as an argument. Add up all the numbers from 1 to the number you passed to the function. For example, if the input is 4 then your function should return 10 because 1 + 2 + 3 + 4 = 10.
### Example

    addUp(4) ➞ 10 
    addUp(13) ➞ 91 
    addUp(600) ➞ 180300
____
# Level 2:
## Bitwise Operations
 	A decimal number can be represented as a sequence of bits.
 To illustrate:
     
   	A decimal number can be represented as a sequence of bits.
	6 = 00000110
    23 = 00010111
## Example
    bitWiseAnd(6,23)=> 00000110
    bitwiseOR(6, 23) ➞ 00010111
    bitwiseXOR(6, 23) ➞ 00010001.
____
# Check if One Array can be Nested in Another
Create a function that returns true if the first array can be nested inside the second.
***arr1 can be nested inside arr2 if***:
1 - arr1's min is greater than arr2's min.
2 - arr1's max is less than arr2's max.
#### Example
    canNest([1, 2, 3, 4], [0, 6]) ➞ true
    canNest([3, 1], [4, 0]) ➞ true
    canNest([9, 9, 8], [8, 9]) ➞ false
    canNest([1, 2, 3, 4], [2, 3]) ➞ false.
____
## Older Than Me
Create a method in the Person object which returns how another person's age compares. Given the instances p1, p2 and p3, which will be initialized with the attributes name and age, return a sentence in the following format:
{other person name} is {older than / younger than / the same age as} me.
### Examples
    p1 = Person("Samuel", 24)
    p2 = Person("Joel", 36)
    p3 = Person("Lily", 24)
    p1.compareAge(p2) ➞ "Joel is older than me."
    p2.compareAge(p1) ➞ "Samuel is younger than me."
    p1.compareAge(p3) ➞ "Lily is the same age as me."
 ____
## Derivative of a Function
Create a function that takes numbers b and m as arguments and returns the derivative of the function f(x)=x^b with respect to x evaluated at x=m, where b and m are constants.
### Examples
    derivative(1, 4) ➞ 1
    derivative(4, -3) ➞ -108
____
## Tuck in Array
Create a function that takes two arrays and insert the second array in the middle of the first array.
### Examples
    tuckIn([1, 10], [2, 3, 4, 5, 6, 7, 8, 9]) ➞ [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    tuckIn([15,150], [45, 75, 35]) ➞ [15, 45, 75, 35, 150]
    tuckIn([[1, 2], [5, 6]], [[3, 4]]) ➞ [[1, 2], [3, 4], [5, 6]]
____
## Find the Amount of Potatoes
Create a function to return the amount of potatoes there are in a string.
### Examples
    potatoes("potato") ➞ 1
    potatoes("potatopotato") ➞ 2
    potatoes("potatoapple") ➞ 1
____
## How Much is True?
Create a function which returns the number of true values there are in an array.
### Examples
    countTrue([true, false, false, true, false]) ➞ 2
    countTrue([false, false, false, false]) ➞ 0
    countTrue([]) ➞ 0
____
## Remove Trailing and Leading Zeros
Create a function that takes in a number as a string n and returns the number without trailing and leading zeros.

Trailing Zeros are the zeros after a decimal point which don't affect the value (e.g. the last three zeros in 3.4000 and 3.04000).
Leading Zeros are the zeros before a whole number which don't affect the value (e.g. the first three zeros in 000234 and 000230).
### Examples
    removeLeadingTrailing("230.000") ➞ "230"
    removeLeadingTrailing("00402") ➞ "402"
    removeLeadingTrailing("03.1400") ➞ "3.14"
    removeLeadingTrailing("30") ➞ "30"
____
## Return the Most Expensive Piece of Jewellery
You go to a jewelry shop and try to find the most expensive piece of jewelry. You write down the name of each piece of jewelry and its price.

Create a function that gets the name of the piece of jewelry with the highest price and returns "The most expensive one is the {name of jewelry piece}".

### Examples
    mostExpensive ({
    "Diamond Earrings": 980,
    "Gold Watch": 250,
    "Pearl Necklace": 4650
    }) ➞  "The most expensive one is the Pearl Necklace"
    
    
    ========================================================
    mostExpensive({
      "Silver Bracelet": 280,
      "Gemstone Earrings": 180,
      "Diamond Ring": 3500
    }) ➞ "The most expensive one is the Diamond Ring"
 
____
## Numbers in Strings
Create a function that takes an array of strings and returns an array with only the strings that have numbers in them. If there are no strings containing numbers, return an empty array.

### Examples
    numInStr(["1a", "a", "2b", "b"]) ➞ ["1a", "2b"]
    numInStr(["abc", "abc10"]) ➞ ["abc10"]
    numInStr(["abc", "ab10c", "a10bc", "bcd"]) ➞ ["ab10c", "a10bc"]
    numInStr(["this is a test", "test1"]) ➞ ["test1"]
    
## Calculate the Total Price of Groceries
Create a function that takes an array of objects (groceries) which calculates the total price and returns it as a number. A grocery object has a product, a quantity and a price, for example:

     {
      "product": "Milk",
       "quantity": 1,
       "price": 1.50
     }
## Examples
     // 1 bottle of milk:
     getTotalPrice([
       { product: "Milk", quantity: 1, price: 1.50 }
     ]) ➞ 1.5

     // 1 bottle of milk & 1 box of cereals:
     getTotalPrice([
       { product: "Milk", quantity: 1, price: 1.50 },
       { product: "Cereals", quantity: 1, price: 2.50 }
     ]) ➞ 4

     // 3 bottles of milk:
     getTotalPrice([
       { product: "Milk", quantity: 3, price: 1.50 }
     ]) ➞ 4.5

     // Several groceries:
     getTotalPrice([
            { product: "Milk", quantity: 1, price: 1.50 },
       { product: "Eggs", quantity: 12, price: 0.10 },
       { product: "Bread", quantity: 2, price: 1.60 },
       { product: "Cheese", quantity: 1, price: 4.50 }
     ]) ➞ 10.4

     // Some cheap candy:
     getTotalPrice([
       { product: "Chocolate", quantity: 1, price: 0.10 },
       { product: "Lollipop", quantity: 1, price: 0.20 }
     ]) ➞ 0.3
____
## Encoded String Parse
Create a function which takes in an encoded string and returns an object according to the following example:

### Examples
    parseCode("John000Doe000123") ➞ {
      firstName: "John",
      lastName: "Doe",
      id: "123"
    }
    -----------------------------------------------
    parseCode("michael0smith004331") ➞ {
      firstName: "michael",
      lastName: "smith",
      id: "4331"
    }
    -----------------------------------------------
    parseCode("Thomas00LEE0000043") ➞ {
      firstName: "Thomas",
      lastName: "LEE",
      id: "43"
    }
