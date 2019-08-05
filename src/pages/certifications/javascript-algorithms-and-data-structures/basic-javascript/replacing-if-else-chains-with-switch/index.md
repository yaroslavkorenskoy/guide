## Replacing If Else Chains with Switch

We have 5 arguments to set in case ('bob', 1, 7, 42, 99)
First of all you must start with 'switch' command

```javascript
switch (val) {}

Then put all arguments inside function.
switch (val) {
case 'bob':
case 1:
case 7:
case 42:
case 99:
}
```

Then set answers inside every case.
```javascript
switch (val) {
case 'bob':
  answer = "Marley";
  break;
case 1:
  answer = "There is no #1";
  break;
...
e.t.c.
```
## SPOILER ALERT! FULL SOLUTION:
```javascript
function chainToSwitch(val) {
  var answer = "";
  // Only change code below this line
  

  switch (val) {
    case 'bob':
      answer = "Marley";
      break;
    case 1:
      answer = "There is no #1";
      break;
    case 42:
      answer = "The Answer";
      break;
    case 7:
      answer = "Ate Nine";
      break;
    case 99:
      answer = "Missed me by this much!";
      break;
    default:
      answer = "";
  }
  // Only change code above this line  
  return answer;  
}

// Change this value to test
chainToSwitch(7);
chainToSwitch(42);
chainToSwitch(1);
chainToSwitch(99);
chainToSwitch("bob");
```
