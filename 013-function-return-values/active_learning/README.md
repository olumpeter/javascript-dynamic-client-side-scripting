# Function return values
    
There's one last essential concept about functions for us to discuss — return 
values. Some functions don't return a significant value, but others do. It's 
important to understand what their values are, how to use them in your code, 
and how to make functions return useful values. 

## What are return values?

**Return values** are just what they sound like — the values that a function 
returns when it completes. You've already met return values several times, 
although you may not have thought about them explicitly.

Let's return to a familiar example (from a previous article in this series):

```js
const myText = 'The weather is cold';
const newString = myText.replace('cold', 'warm');
console.log(newString); // Should print 'The weather is warm'
// the replace() string function takes a string,
// replaces one substring with another, and returns
// a new string with the replacement made
```

The `replace()` function is invoked on the `myText` string, and is passed 
two parameters:

  - The substring to find ('cold')
  - The string to replace it with ('warm')

When the function completes (finishes running), it returns a value, which is 
a new string with the replacement made. In the code above, the result of this 
return value is saved in the variable `newString`.

If you look at the `replace()` function MDN reference page, you'll see a 
section called `return value`. It is very useful to know and understand what 
values are returned by functions, so we try to include this information 
wherever possible.

Some functions don't return any value. (In these cases, our reference pages 
list the return value as `void` or `undefined`.) For example, in the 
`displayMessage()` function we built in the previous article, no specific 
value is returned when the function is invoked. It just makes a box appear 
somewhere on the screen — that's it!

Generally, a return value is used where the function is an intermediate 
step in a calculation of some kind. You want to get to a final result, which 
involves some values that need to be calculated by a function. After the 
function calculates the value, it can return the result so it can be stored 
in a variable; and you can use this variable in the next stage of the 
calculation.

## How you can access this live website

<dl>
  Use the following URL:
  <dd>
    https://olumpeter.github.io/javascript-dynamic-client-side-scripting/013-function-return-values/active_learning/
  </dd>
  or click the following link:
  <dd>
    <a href="https://olumpeter.github.io/javascript-dynamic-client-side-scripting/013-function-return-values/active_learning/">Visit website</a>
  </dd>
</dl>
