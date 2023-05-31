# [1. A Needle in the Haystack](https://www.codewars.com/kata/56676e8fabd2d1ff3000000c/train/javascript)

```js
function findNeedle(haystack) {
  let FindingNeedle = haystack.indexOf("needle");
  return `found the needle at position ${FindingNeedle}`;
}
```

# [2. 5 without numbers !!](https://www.codewars.com/kata/59441520102eaa25260000bf/train/javascript)

```js
function unusualFive() {
  const a = "hello";
  return a.length;
}
```

# [3. Highest and Lowest](https://www.codewars.com/kata/554b4ac871d6813a03000035/train/javascript)

```js
function highAndLow(numbers) {
  let ConvertToNumber = numbers.split(" ").map(Number);
  let MaxNumber = Math.max(...ConvertToNumber);
  let MinNumber = Math.min(...ConvertToNumber);
  return `${MaxNumber} ${MinNumber}`;
}
```

# [4. Is it even?](https://www.codewars.com/kata/555a67db74814aa4ee0001b5/train/javascript)

```js
function testEven(n) {
  return n % 2 === 0 && Number.isInteger(n);
}
```
