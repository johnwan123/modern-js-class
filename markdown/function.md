## [Function 函式](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)
#### 函式其實就是個小程式。函式做的事情就是－
#### 丟入參數，回傳結果

```javascript
function name(param1, param2) {
  // statements
  return 42;
}
```

```javascript
const name = function(param1, param2) {
  // statements
  return 42;
}
```

---

## [Arrow Function 箭頭函式](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

```javascript
(param1, param2) => {
  // statements
   return 42;
}
```

```javascript
const name = (param1, param2) => {
  // statements
  return 42;
}
```
```javascript
const name = (param1, param2) => {
  42;
}
```

---

#### 定義函式，使用函式
#### .() 是呼叫的意思，如果沒有呼叫就是一個函式物件

```javascript
const max = (number1, number2) => {
  if (number1 > number2) {
    return number1;
  } else {
    return number2;
  }
}

console.log(max(1, 10));
console.log(max(10, 1));
console.log(max);
```

---

#### 定義函式，使用函式2

```javascript
const printNumber = (number) => {
  console.log(number);
}

let numbers = [97, 1, 50, 90, 100, -5, -20 ,9, 0];

numbers.forEach(printNumber);
```
---

#### 定義函式，使用函式3

```javascript
let numbers = [97, 1, 50, 90, 100, -5, -20 ,9, 0];

numbers.forEach((number) => {
  console.log(number);
});
```
---

#### 定義函式，使用函式4

```javascript
let numbers = [97, 1, 50, 90, 100, -5, -20 ,9, 0];
let reversed = [];

numbers.forEach((item)=>{
  reversed.unshift(item);
});

console.log(numbers);
console.log(reversed);
```

---

#### 小測驗1.