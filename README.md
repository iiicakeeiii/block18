# block18 Workshop - Writing Tests Specifications

### Unit Testing (Expect [action] to be [some result]):
1. A function called "multiplication" that returns the product of the two input numbers.
 - Expect the function "multiplication" to be a number.
 - Expect the function "multiplication" to be the product of two numbers.
 - Expect multiplication(2,3) to be the number 6.
 - Expect multiplication(2,'a') to be an error.
   
2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
 - Expect the function "concatOdds" to be one array.
 - Expect the function "concatOdds" to be an array of odd numbers.
 - Expect the function "concatOdds" to be able to accept two arrays.
 - Expect the function "concatOdds" to be able to iterate to iterate through arrays.
 - Expect the function "concatOdds" to be able to accept negative numbers.
 - Expect the function "concatOdds" to be an array of unique numbers.
 - Expect concatOdds([1,1,2,3],[4,5,6]) to be an array of [1,3,5].
 - Expect concatOdds(['a',[2]],["three", 4]) to be an error.

### Functional Testing (When a user [does something with some parameters], [some thing should happen]):
1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
