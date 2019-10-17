[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly)

---
Title: Sum & Count <br>
Type: Coding Challenge <br>
Duration: "~:30" <br>
Creator: Kenneth Cruz <br>
Source: Code Wars <br>
PreReq: JavaScript Fundamentals


## Ordered Sum 
Given two integers a and b, which can be positive or negative, find the sum of all the numbers **between** including them too and return it. If the two numbers are equal return a or b. <br>

Note: a and b are not ordered! <br>

```javascript
GetSum(1, 0) == 1   // 1 + 0 = 1
GetSum(1, 2) == 3   // 1 + 2 = 3
GetSum(0, 1) == 1   // 0 + 1 = 1
GetSum(1, 1) == 1   // 1 Since both are same
GetSum(-1, 0) == -1 // -1 + 0 = -1
GetSum(-1, 2) == 2  // -1 + 0 + 1 + 2 = 2
```

## Count characters in your string

The main idea is to count all the occurring characters(UTF-8) in string. If you have string like `aba` then the result should be <br>
```javascript
{ 'a': 2, 'b': 1 }
```
<br>

What if the string is empty ? Then the result should be empty object literal { } <br>