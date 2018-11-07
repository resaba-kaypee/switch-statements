# switch-statements
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
    case 1:
    answer = "alpha";
    break;
    case 2:
    answer = "beta";
    break;
    case 3:
    answer = "gamma";
    break;
    case 4:
    answer = "delta";
    break;
  }
    return answer;  
}
  
  
console.log(caseInSwitch(1));
console.log(caseInSwitch(2));
console.log(caseInSwitch(3));
console.log(caseInSwitch(4));


Basic JavaScript: Multiple Identical Options in Switch Statements
If the break statement is omitted from a switch statement's case, the following case statement(s) are executed until a break is encountered. If you have multiple inputs with the same output, you can represent them in a switch statement like this:

function sequentialSizes(val) {
  var answer = "";
  // Only change code below this line
  switch (val) {
    case 1:
    case 2:
    case 3:
    answer = "Low";
    break;
    case 4:
    case 5:
    case 6:
    answer = "Mid";
    break;
    case 7:
    case 8:
    case 9:
    answer = "High";
    break;
  }
  
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
console.log(sequentialSizes(5));
