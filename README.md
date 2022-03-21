# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

*Summary*
1) The function takes an input `months`, a number data type.
2) The function checks if the number is less than or equal to 3, and if not, the function checks if the number iless than or equal to 6, then 9, and then finally 12. 
3) Depending on which came back true, the function returns either `1, 2, 3, or 4`. If none of the statements are true, the function will return `undefined`. 

```js
function (month){
  if (month <= 3){
    return 1
  } else if (month <= 6){
    return 2
  } else if (month <= 9){
    return 3
  } else if (month <= 12){
    return 4
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output    |
| ----- | --------- |
|  3    |  1        | 
|  7    |  3        | 
|  13   | undefined |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program tells you which quarter the specified month is in.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
