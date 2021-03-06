# [Storing Values with the Assignment Operator](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/storing-values-with-the-assignment-operator)

In JavaScript, you can store a value in a variable with the _assignment_ operator.

```js
myVariable = 5;
```

This assigns the `Number` value `5` to `myVariable`.

Assignment always goes from right to left. Everything to the right of the `=` operator is resolved before the value is assigned to the variable to the left of the operator.

```js
myVar = 5;
myNum = myVar;
```

This assigns `5` to `myVar` and then resolves `myVar` to `5` again and assigns it to `myNum`.

---

Assign the value `7` to variable `a`.

Assign the contents of `a` to variable `b`.


## Setup

```js
var a;
var b = 2;
```

## Solution

```js
a = 7;
b = a;

// 7
```