## Return Negative

```js
function makeNegative(num) {
  if (num < 0) {
    return num * 1
  } else {
    return num * -1
  }
}
makeNegative()
```

## Sum of Positive

```js
function positiveSum(arr) {
let sum = 0;
    for (let i = 0; i < arr.length; i++)
        if (arr[i] > 0) {
            sum += arr[i];
        }
    return sum
}
positiveSum()
```

## Function 2

```js
const square = n => n ** 2

square()

```

## Sum Arrays

```js
function sum (numbers) {
   let sum = 0;
    for (let i = 0; i < numbers.length; i++) {
        sum += numbers[i]
    } 
       return sum;
    
}
sum()
```

## Reversed Strings

```js
//https://www.freecodecamp.org/news/how-to-reverse-a-string-in-javascript-in-3-different-ways-75e4763c68cb/

function solution(str){
  return str.split("").reverse().join("")
  }

solution()

```
