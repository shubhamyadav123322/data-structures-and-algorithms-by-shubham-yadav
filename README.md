# 🚀 Day 1 - Programming Basics

This file documents the concepts I practiced on **Day 1** of my coding journey.

## 📚 Topics Covered
1. **Loops**
   - For loop
   - While loop
   - Do-while loop  

2. **Functions**
   - Defining and calling functions
   - Parameters and return values

3. **Booleans**
   - Boolean values (`true` / `false`)
   - Logical operators (`&&`, `||`, `!`)

4. **Arrays**
   - Creating arrays
   - Accessing and modifying elements
   - Looping through arrays

5. **Data Types**
   - Numbers
   - Strings
   - Booleans
   - Arrays
   - Objects (introduction)

6. **If-Else Statements**
   - Simple `if`
   - `if-else`
   - `if-else if` ladder
   - Nested conditions

## 📝 Notes
- Loops are useful when repeating tasks.
- Functions help organize code and avoid repetition.
- Booleans control decision-making in programs.
- Arrays store multiple values in a single variable.
- Conditional statements (`if-else`) let programs make decisions.

## 💡 Example
```js
// Example: Check if a number is even or odd using function & if-else
function checkNumber(num) {
  if (num % 2 === 0) {
    return "Even";
  } else {
    return "Odd";
  }
}

console.log(checkNumber(5)); // Output: Odd
console.log(checkNumber(10)); // Output: Even
