# ES6-lectures
A series on lectures on ES6 and JS fundamentals I did for Flatiron School Students


///// IS THIS SYNTAX CORRECT? //////

// function addTwoNumbers(number, otherNumber) {
//   return number + otherNumber 
// }

// Is this syntax correct?!
// function(num){return num}(5)

// addTwoNumbers(3,4);

// function addThree(num){num + 3}
// addThree(5);

// Can I do maths on functions saved to a variable?
// const y = addTwoNumbers(2, 1) *2 ;
// const x = addTwoNumbers("banana", "apple");
// y.toString()













// WHAT IS A FUNCTION? 

// WHAT IS A FUNCTION DECLARATION? 
// function doSomething (num){
// 	return num
// }

// doSomething(5)
// function +return statement and the parameters

// WHAT IS A FUNCTION EXPRESSION?
// const thisIsAnExpression = doSomething(num)

// WHAT ARE PARAMETERS? ARGUMENTS?










/////   HOW DO I CREATE AN ARROW FUNCTION? HOW DO I ADD A NAME TO THE ARROW FUNCTION?/////  
// rewrite the functions above to arrow functions

// function addTwoNumbers(number, otherNumber) {
// 	let newNumber = number * 2
//   return newNumber + otherNumber 
// }

// const addTwoNumbers = (number, otherNumber)=> number + otherNumber

// let addTwoNumbers = (number, otherNumber) => {
// 	let newNumber = number * 2 
// 	return newNumber + otherNumber 
// }

// function addTwoNumbers(number) {
// 	return number
// }

// const addTwoNumbers = number => number


// addTwoNumbers(1)


// function(num){return num}(5)


// function addThree(num){num + 3}
// addThree(5);










// is this syntax correct?!
// _ => 42

// what is happening here?
// let setNameIdsEs6 = (cat, yay) => ({ cat, yay});
// setNameIdsEs6(1, "Annie")


///// HOISTING - WILL THIS WORK? ///// 

// willItWorkFunction(5);

// function willItWorkFunction(y) {
//   return y * y;
// }

// willItWorkFunction = y => y * y

// willItWorkFunction(5);














//////// When do I need { } curly braces with an arrow function? When can I skip them?
///// Under what circumstances will an arrow function implicitly return?


//////// can I define a default parameter for a JS function? When will it be used?

function greet(name = "Ginger Spice") {
  return `Hello, ${ name }`
}

// let's rewrite it into an arrow function

// greet()

// console.log(greet)
// console.log(greet())

// console.log(greet("Sylwia"))
// console.log(greet(null))
// console.log(greet(false))
// console.log(greet(0))
// console.log(greet(NaN))
// console.log(greet(""))
console.log(greet(undefined))











// /*
  // const spiceGirls = ["Scary", "Baby", "Ginger", "Posh", "Sporty"]

  // const callback = function(adjective){ adjective + "SPICE" }
  // const callback = function(){ }

  // const callback = function(adjective) { adjective.toUpperCase() + " SPICE" }
  // const callback = adjective => { adjective.toUpperCase() + " SPICE" }
  // const callback = (adjective) => { return adjective.toUpperCase() + " SPICE" }
  // const callback = (adjective) => adjective.toUpperCase() + " SPICE";
  // const callback = adjective => adjective.toUpperCase() + " SPICE";
  
  // const bigNastyString = spiceGirls
  //   .map(callback)
  //   .join(" and ")

  // console.log(bigNastyString);



