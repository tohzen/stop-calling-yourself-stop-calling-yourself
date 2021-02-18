# Calling Your Own Functions

### Setup

CREATE YOUR OWN `main.js` file and work within there.

For each of the following tasks:

1. Write the function.
2. Use Quokka to "print out" the results (i.e., make the results appear next to your code).
3. Repeat steps 1 and 2 for EACH of the example inputs given for EACH function in the tasks section below. (See the example below for how you might print out each result.)

Quokka should print out those return values for you ( the strings with the three question marks, in this example). Note that ALL example inputs are being tested, not just one!

For example, for the first task, if you called your function questionHard (don't call it that, that's a terrible name), your screenshot would look like the following code:

```javascript
let result1 = questionHard('hello')
let result2 = questionHard('what even')
result1   'hello???'
result2   'what even???'
```

If you really don't like Quokka, you can, alternately:

1. Write the function.
2. `console.log` the result of calling the function (in the example above, you'd `console.log` `result1` and `result2`) and run `node main.js` in your terminal to see the results printed out there.
3. Repeat steps 1 and 2 for EACH of the example inputs given for EACH function in the tasks section below. (See the example below for how you might print out each result.)

Note that you can call the functions whatever you want! Try to name them well? Take 30 seconds to think about reasonable names for them.

### Tasks

- add three question marks to the string
  - 'hello' -> 'hello???'
  - 'what even' -> 'what even???'
- add two strings with a space in the middle
  - 'oh', 'hi' -> 'oh hi'
  - 'well', 'hello back' -> 'well hello back'
- subtract three numbers
  - 10, 1, 2 -> 7
  - 8, 3, 5 -> 0
  - 100, 80, 25 -> -5
- subtract three numbers in reverse order
  - 10, 1, 2 -> -9
  - 2, 1, 10 -> 7
- triple a string
  - 'codeimmersives' -> 'codeimmersivescodeimmersivescodeimmersives'
  - 'is the best' -> 'is the bestis the bestis the best'
- return the square root of a number (you'll probably need research!)
  - 16 -> 4
  - 4 -> 2
  - 9 -> 3
