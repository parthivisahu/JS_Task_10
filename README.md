# JS_Task_10
# Displaying JavaScript Outputs in Console

This guide provides examples of different ways to display JavaScript outputs in the console, using various techniques and console methods.

## Usage

1. Open your browser's developer console by right-clicking on the webpage and selecting "Inspect" or by pressing `Ctrl + Shift + J` (or `Cmd + Option + J` on macOS).

2. Use the following methods to display outputs in the console:

### 1. `console.log()`

The `console.log()` method is commonly used to display messages, variables, or other data in the console.

```javascript
console.log('Hello, world!');
```

Output:
```
Hello, world!
```

### 2. `console.info()`

The `console.info()` method is similar to `console.log()` and can be used to display informational messages.

```javascript
console.info('Informational message');
```

Output:
```
ℹ Informational message
```

### 3. `console.warn()`

The `console.warn()` method is used to display warning messages.

```javascript
console.warn('Warning: Something went wrong!');
```

Output:
```
⚠ Warning: Something went wrong!
```

### 4. `console.error()`

The `console.error()` method is used to display error messages.

```javascript
console.error('Error: Something went wrong!');
```

Output:
```
❌ Error: Something went wrong!
```

### 5. `console.table()`

The `console.table()` method is used to display tabular data in a table format.

```javascript
const data = [
  { name: 'John', age: 30 },
  { name: 'Jane', age: 25 },
  { name: 'Adam', age: 35 }
];

console.table(data);
```

Output:
```
(index)  name  age
-------  ----  ---
0        John  30
1        Jane  25
2        Adam  35
```

### 6. String substitution with `%s`, `%d`, `%f`

You can use string substitution in the `console.log()` method to display dynamic values in a formatted string.

```javascript
const name = 'John';
const age = 25;

console.log('Name: %s, Age: %d', name, age);
```

Output:
```
Name: John, Age: 25
```

## Examples

```javascript
console.log('Hello, world!');
console.info('Informational message');
console.warn('Warning: Something went wrong!');
console.error('Error: Something went wrong!');

const data = [
  { name: 'John', age: 30 },
  { name: 'Jane', age: 25 },
  { name: 'Adam', age: 35 }
];
console.table(data);

const name = 'John';
const age = 25;
console.log('Name: %s, Age: %d', name, age);
```

The above examples demonstrate different ways to display outputs in the console using various console methods.

Feel free to experiment and combine these techniques to suit your specific debugging or logging needs in JavaScript.
