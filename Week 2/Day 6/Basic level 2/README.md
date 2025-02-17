# Basic Level 2 Assignment

### Theory

### Why do we use functions in **JavaScript**?

> In JavaScript, a function allows you to define a block of code, give it a name and then execute it as many times as you want. A JavaScript function can be defined using _function_ keyword.

**Example:**

>function multiply(num1,num2) { <br>
>let result = num1 \* num2;<br>
>return result;<br>
>}

### What is Function Invocation?

> The function invocation is used to execute the code inside the curly braces in the function definition by adding () after function name after it has been defined to invoke that particular function.

**Example:**

>function car( color ) {<br>
> return color;<br>
>}<br>
>car( red );

### Does a function behave like an object in Javascript? Prove it by an example.

> In JavaScript, functions are called Function Objects because they are objects. Just like objects, functions have properties and methods, they can be stored in a variable or an array, and be passed as arguments to other functions.

**Example:**

>function message() {<br>
> console.log("Greetings!");<br>
>}<br>
>console.log(typeof message); // => function<br>
>console.log(message instanceof Object); // => true<br>
>console.log(message instanceof string); // => false

### What are Events in Javascript?

> JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

### What is a string?

> A JavaScript string stores a series of characters.
> A string can be any text inside double or single quotes
> Normally, strings like "you can do it", cannot have methods or properties because they are not objects.JavaScript treats strings as objects when executing methods and properties.
> The first character is in position 0, the second in 1, and so on.

**Example:**
> let care1 = "bmw";
> let car2 = 'audi';

### What is an array? Is it static or dynamic in Javascript?

> In JavaScript, array is a single variable that is used to store different elements.It is often used when we want to store list of elements and access them by a single variable. Like all scripting languages​​, JavaScript has dynamic arrays as neither their size is predetermined, nor the type of data.

### Difference between map and set in javascript?

> A **Set** is a collection dataset that needs to be composed of unique values,where a **Map** is when you have pairs of associated data when we map the keys to the value.

### Difference between Array and Map?

> **map()** creates a new array with the results of calling a provided function on every element in this array.
> **Array** An array is a collection of items stored at contiguous memory locations.

### What are array methods? List a few names?

> Array methods are the operations on array for particular task.

1. sort(): Sorts the elements of an array.
2. reverse(): Reverses the order of the elements in an array
3. indexOf() Search the array for an element and returns its position
4. find(): Returns the value of the first element in an array that pass a test etc.

### In how many ways can we traverse through an array in Javascript?

> There are multiple ways one can iterate over an array in Javascript. The most useful ones are mentioned below :
1. Using while loop.
2. Using forEach method.
3. Using every method.
4. Using map.
