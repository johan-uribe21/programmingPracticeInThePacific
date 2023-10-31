# Programming Practice Probelems

## Homework 1

1. For a given input array of integers, return an array where each value of the input array is multipled by 5
```javascript
function problemOne(arr){
  // your code here
}

console.log(problemOne([2, 5, 100])); // [10, 25, 500]
```

2. For a given input array of integers, return an array where each value of the input array is multipled by 10 and turned into a string
```javascript
function problemTwo(arr){
  // your code here
}

console.log(problemTwo([2, 5, 100])); // ['200', '500', 1000']
```

3. For a given input array of integers, return an array where each value of the input array is doubled if it is odd and halved if it is even
```javascript
function problemThree(arr){
  // your code here
}

console.log(problemThree([2, 5, 100])); // [1, 10, 50]
```

4. Each person object contains three fields: firstName, lastName, and age. For a given input array of person objects, return an array of strings in the following format: `"lastName, firstName - age"`
```javascript
person1 = {
  firstName: 'Paul',
  lastName: 'Kimmle',
  age: 36
}
person2 = {
  firstName: 'Jane',
  lastName: 'Dion',
  age: 21
}
function problemFour(personsArray){
  // your code here
}

console.log(problemFour([person1, person2])); // ['Kimmle, Paul - 36', 'Dion, Jane - 21']
```