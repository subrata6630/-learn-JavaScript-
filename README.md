# learn-JavaScript


### What Is JavaScript?

JavaScript is a high level programming language used to create interactive effects within web browsers
Can be used on the server and in more complicated environments that are not web based such as PDF docs, site-specific browsers and desktop widgets



### JavaScript Output

<ul>
    <li>console.log(‘some value’) – Prints to console in browser or terminal</li>
    <li>window.alert() – Displays in an alert box in the browser</li>
    <li>document.write() – Display within <script> tags in the html</li>
    <li>innerHTML – Access an html element using document.getElementById() and output to it</li>
</ul>


### The JavaScript Language


### Expressions

An expression is a combination of values, variables and operators which computes a value

```JavaScript
2 * 5
x * 5
“Hello”+ “  ” + “World”

```

### Comments

Single Line Comment
var x = 5; // This is a single line comment

Multi Line Comment
/*
	This is a
	multi-line comment
*/


### Arrays
JavaScript arrays allow us to store multiple values in a single variable

```JavaScript
var names = [‘Bob’, ‘Jim’, ‘Jose’, ‘Paula’];

console.log(names[0]);    // Bob

```
### Loops

Execute a block of code as long as a condition is true and repeat

```JavaScript
For Loop:
for(I = 0; I < 10;i++){
	console.log(i)
}

While Loop:
while(I < 10){
	console.log(i);
	i++’
}

```


### Conditionals / If Statements


Runs a block of code if something is true
```JavaScript


var x = 10;
If(x > 5){
	console.log(‘Yes’);
}

If(x > 5){
	console.log(‘Yes’);
} else {
	console.log(‘No’);
}


```
### Switch


Selects one of many blocks of code to execute. Often used as an alternative for an if statement
```JavaScript

Switch(x){
	case 1:
		console.log(‘Yes x is 1’);
		break;
	case 2:
		console.log(‘Yes x is 2’);
		break;

	default:
		console.log(No x is not 1 or 2);
		break;
}

```
### Function

Block of code designed to run a task. Can be created and then invoked later on

```JavaScript

function sayHello(){
	console.log(‘Hello World’);
}

function sayHello(greeting){
	console.log(greeting);
}




```

