#Outline for Wednesday 9/16
- Recap yesterday, go over homework
- In Class Basic JS Exercise
- Introduce Arrays
- In Class Array Exercise (pairs)

##Homework
```javascript
//1. Log your name to the console (as a string).

//2. Declare a variable called name, log it to the console.

//3. Declare two variables with number values. Add, subtract, multiply and divide them.

//4. Declare two variables with string values. Create a third variable that concatenates them.

//5. Add, subract, multiply and divide the strings '5' and '3'. Observe and explain the results.

//6. Create a prompt that asks a user to pick a number. Double the answer.

//7. Create a custom alert.

//8. Declare three variables called length, width and height. Calculate area and volume.

//9. Ask for a user's name, age and city. In a single command display/log the sentence:
// "My name is...I'm....years old, and I live in....."

//10. Create an alert that uses the response from a prompt.
```
##Carryover from Monday
Strings can be added just like numbers, this is called `concatenation`.
```javascript
var addWords = 'Look!' + ' I am a concatenated string!';
console.log(addWords);

//Look! I am a concatenated string!


//Concatenation works with variables as well, provided they are strings.
var person = 'David';
var greetPerson = 'Hello ' + person + '!';
console.log(greetPerson);

// Hello David!
```
When an operator is applied to the “wrong” type of value, JavaScript will quietly convert that value to the type it wants, using a set of rules that often aren’t what you want or expect. This is called `type coercion`

```javascript
console.log(8 * null)
//  0
console.log("5" - 1)
//  4
console.log("5" + 1)
//  51
console.log("five" * 2)
//  NaN
console.log(false == 0)
//  true

```
###document.write() vs console.log()
```javascript
document.write('Hello World');
// appends string to body element of page
console.log('Hello World');
// displays string in console
```
When would you want to use console.log? Document write?

###prompt() and alert()
```javascript
prompt('What is your name?');
// opens modal for user to type in
var name = prompt('What is your name?');
// sets name variable equal to the typed response
alert('This is a test!');
// opens modal with message 'This is a test!'
```
##Variables

##console.log();

##Arrays

##Array Exercise
