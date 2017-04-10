# JavaScript: Function Basics

## Jen Shannon

---

# Objectives

1. Differentiate between a JavaScript function declaration and invocation
2. Declare and invoke a JavaScript function that takes arguments and returns a value

---

# JavaScript Functions

* Group related statements together to perform a task
* Are defined with the `function` keyword
* Executed when the function is invoked/called

---

# JavaScript Function Declaration

Defines a function. Does not execute it.

```JavaScript
//function declaration
function greeting(){
  console.log('Hello!');
}

```
---

# Invoke/Call a function

Statements in the block are not run until the function is called.

```JavaScript
//function invocation
greeting();

```

---

# Let's code...

---

# Challenge: Create some old school annoyware

* Declare a function that uses the built-in alert method to alert the user that they have won a valuable prize
* Invoke the function a few times

---

# Functions can have inputs

```JavaScript
//function declaration
function persGreet(firstName, lastName){
  console.log('Hello ' + firstName + ' ' + lastName);
}

//function invocation
persGreet('Jen', 'Shannon');

```

---

# Parameters and arguments

* We define parameters
* We pass in arguments

---

# Let's code...

---

# Return Statement

* Stops the execution of function
* Can return a value

---

# Put it together

```JavaScript
//function declaration
function addNums(num1, num2) {
  return num1 + num2;
}

//function invocation
var sumOne = addNums(3,5);
var sumTwo = addNums(4,8);
```

---

# Let's code...


---

# Exercises

* Declare a JavaScript function called sub that when given two numbers as inputs, returns their difference.

* Declare a JavaScript function called isBig that when given a number as an input, returns `true` if the number is greater than 100 and `false` if it is not.
