# Chai or Code - 30 days js challege

# Day 1: Variables and Data Types

## Activity 1: Variable Declaration

### Task 1: Declare a variable using var, assign it a number, and log the value to the console.

```js
var price = 30;
console.log(price);
```

### Task 2: Declare a variable using let, assign it a string, and log the value to the console.

```js
let myName = "Shamim";
console.log(myName);
```

## Activity 2: Constant Declaration

### Task 3: Declare a variable using const, assign it a boolean value, and log the value to the console.

```js
const isAbeliever = true;
console.log(isAbeliever);
```

## Activity 3: Data Types

### Task 4: Create variables of different data types (number, string, boolean, object, array) and log each variable's type using the typeof operator.

```js
const number = 30;
const string = "string";
const boolean = true;
const obj = {
  name: "Shamim",
  city: "Dhaka",
};
const arr = [3, 5, 7];

console.log(typeof number); // number
console.log(typeof string); // string
console.log(typeof boolean); // boolean
console.log(typeof obj); // object
console.log(typeof arr); // object
```

## Activity 4: Reassigning Variables

### Task 5: Declare a variable using let, assign it an initial value, reassign a new value, and log both values to the console.

```js
let price = 30;
console.log(price);
price = 50;
console.log(price);
```

## Activity 5: Understanding const

### Task 6: Try reassigning a variable declared with const and observe the error.

```js
const price = 30;
console.log(price);
price = 50;
// Uncaught TypeError: Assignment to constant variable.
```

## Feature Request:

1. Variable Types Console Log: Write a script that declares variables of different data types and logs both the value and type of each variable to the console.

```js
const number = 30;
const string = "string";
const boolean = true;
const obj = {
  name: "Shamim",
  city: "Dhaka",
};
const arr = [3, 5, 7];

console.log("value:", number, "type:", typeof number);
console.log("value:", string, "type:", typeof string);
console.log("value:", boolean, "type:", typeof boolean);
console.log("value:", obj, "type:", typeof obj);
console.log("value:", arr, "type:", typeof arr);
```

2. Reassignment Demo: Create a script that demonstrates the difference in behavior between let and const when it comes to reassignment.

```js
// let
let info = "Hello, world!";
console.log(info); // Hello, world!

info = "This info has been changed.";
console.log(info); // This info has been changed.

// const
const gravity = 9.8;
console.log(gravity); // 9.8

gravity = 10; // This will cause an error
console.log(gravity); // This line will not execute
```

## Achievement:

By the end of these activities, you will:

- know how to declare variables using var, let, and const.
- Understand the different data types in JavaScript.
- Be able to use the typeof operator to identify the data type of a variable.
- Understand the concept of variable reassignment and the immutability of const variables.
