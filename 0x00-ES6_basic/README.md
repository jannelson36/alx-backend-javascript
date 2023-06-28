# ES6 Basics

This sub folder contains assignments on the basics of ECMAScript 2015 (ES6).

## Tasks To Complete

+ [x] 0. **Const or let?**<br/>[0-constants.js](0-constants.js) includes a script that fulfills the following requirements.
  + For the code below, make the following modifications:
    + function `taskFirst` to instantiate variables using `const`.
    + function `taskNext` to instantiate variables using `let`.
  

+ [x] 1. **Block Scope**<br/>[1-block-scoped.js](1-block-scoped.js) includes a script that fulfills the following requirements.
  + For the code below, modify the variables inside the function `taskBlock` so that the variables aren't overwritten inside the conditional block.


+ [x] 2. **Arrow functions**<br/>[2-arrow.js](2-arrow.js) includes a script that fulfills the following requirements.
  + For the code below, rewrite the following standard function to use ES6's arrow syntax of the function `add`.


+ [x] 3. **Parameter defaults**<br/>[3-default-parameter.js](3-default-parameter.js) includes a script that fulfills the following requirements.
  + For the code below, condense the internals of the following function to 1 line - without changing the name of each function/variable.


+ [x] 4. **Rest parameter syntax for functions**<br/>[4-rest-parameter.js](4-rest-parameter.js) includes a script that fulfills the following requirements.
  + For the code below, modify the following function to return the number of arguments passed to it using the rest parameter syntax.


+ [x] 5. **The wonders of spread syntax**<br/>[5-spread-operator.js](5-spread-operator.js) cincludes a script that fulfills the following requirements.
  + For the code below, using spread syntax, concatenate 2 arrays and each character of a string by modifying the function below. The function body should be one line long.
  

+ [x] 6. **Take advantage of template literals**<br/>[6-string-interpolation.js](6-string-interpolation.js) includes a script that fulfills the following requirements.
  + For the code below, rewrite the return statement to use a template literal so you can the substitute the variables you’ve defined.
 

+ [x] 7. **Object property value shorthand syntax**<br/>[7-getBudgetObject.js](7-getBudgetObject.js) includes a script that fulfills the following requirements.
  + For the code below, modify the following function’s `budget` object to simply use the keyname instead.


+ [x] 8. **No need to create empty objects before adding in properties**<br/>[8-getBudgetCurrentYear.js](8-getBudgetCurrentYear.js) includes a script that fulfills the following requirements.
  + For the code below, rewrite the `getBudgetForCurrentYear` function to use ES6 computed property names on the `budget` object.
 

+ [x] 9. **ES6 method properties**<br/>[9-getFullBudget.js](9-getFullBudget.js) includes a script that fulfills the following requirements.
  + For the code below, rewrite `getFullBudgetObject` to use ES6 method properties in the `fullBudget` object.


+ [x] 10. **For...of Loops**<br/>[10-loops.js](10-loops.js) includes a script that fulfills the following requirements.
  + For the code below, rewrite the function `appendToEachArrayValue` to use ES6’s `for...of` operator. And don’t forget that `var` is not ES6-friendly.
 

+ [x] 11. **Iterator**<br/>[11-createEmployeesObject.js](11-createEmployeesObject.js) includes a script that fulfills the following requirements.
  + Write a function named `createEmployeesObject` that will receive two arguments:
    + `departmentName` (String).
    + `employees` (Array of Strings).


+ [x] 12. **Let's create a report object**<br/>[12-createReportObject.js](12-createReportObject.js) includes a script that fulfills the following requirements.
  + Write a function named `createReportObject` whose parameter, `employeesList`, is the return value of the previous function `createEmployeesObject`.

  + `createReportObject` should return an object containing the key `allEmployees` and a method property called `getNumberOfDepartments`.
  + `allEmployees` is a key that maps to an object containing the department name and a list of all the employees in that department. If you’re having trouble, use the spread syntax.
  + The method property receives employeesList and returns the number of departments.

+ [x] 13. **Iterating through report objects**<br/>[100-createIteratorObject.js](100-createIteratorObject.js) includes a script that fulfills the following requirements.
  + Write a function named `createIteratorObject`, that will take into argument a report Object created with the previous function `createReportObject`.
 
  + This function will return an iterator to go through every employee in every department.

+ [x] 14. **Iterate through object**<br/>[101-iterateThroughObject.js](101-iterateThroughObject.js) includes a script that fulfills the following requirements.
  + Write a function named `iterateThroughObject`. The function’s parameter `reportWithIterator` is the return value from `createIteratorObject`.

  + It should return every employee name in a string, separated by ` | `.
