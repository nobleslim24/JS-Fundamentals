# JS-Fundamentals

This project contains JavaScript scripts that demonstrate basic concepts such as variables, printing, and more.

## Task 0 - First constant, first print

This task prints a string using a constant variable and `console.log`.

# JS-Fundamentals 
## Task 1 - Multi-line Print

This script prints 3 lines using `console.log`:

```javascript
console.log("C is fun");
console.log("Python is cool");
console.log("JavaScript is amazing");

## Task 4 - Create a sentence

This script prints two arguments in the format: `"arg1 is arg2"`

```javascript
const arg1 = process.argv[2];
const arg2 = process.argv[3];

console.log(`${arg1} is ${arg2}`);
## Task 5 - An Integer

This script prints the first argument converted to an integer, or "Not a number" if it can't be converted.

```javascript
const arg = process.argv[2];
const num = parseInt(arg);

if (!isNaN(num)) {
  console.log(`My number: ${num}`);
} else {
  console.log("Not a number");
}

## Task 6 - Loop to languages

This script prints 3 language lines using a loop and one `console.log`:

```javascript
const messages = ["C is fun", "Python is cool", "JavaScript is amazing"];

for (let i = 0; i < messages.length; i++) {
  console.log(messages[i]);
}
