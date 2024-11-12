## **Description:**
Strict equality (===) is a powerful tool in JavaScript for precise value comparison. Unlike loose equality, it does not perform automatic type coercion. This means that 3.14 and "3.14" are considered different values because they have different data types.

## Technologies used:
*  `Html`
*  `JavaScript`


To get started, we need to create 2 types of files: index.html and index.js after which we will attach our javascript file to the html code with a command such as: 
```
JavaScript
// === strict equalityy operator ( compare if values & datatype are equal )
const PI = 3.14;

if (PI == "3.14") {
console.log("That is PI");
}
else {
console.log("That is NOT Pi");
}
```
