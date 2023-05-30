# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```
## OUTPUT
![calcul sc-1](https://github.com/kaviyaelumalai/Ex07_Web-Design/assets/127817032/08854071-c49a-4a69-a803-fe5ffb950e79)
![calcul sc-2](https://github.com/kaviyaelumalai/Ex07_Web-Design/assets/127817032/392f90fd-0553-4386-bbfe-f2708af915a7)
![calcul sc-3](https://github.com/kaviyaelumalai/Ex07_Web-Design/assets/127817032/d6d713fc-90e4-4d56-924c-5d8421e20178)
![cacul sc -4](https://github.com/kaviyaelumalai/Ex07_Web-Design/assets/127817032/bcf932cc-b7ea-436d-b507-e5783828360c)
![calcul sc-5](https://github.com/kaviyaelumalai/Ex07_Web-Design/assets/127817032/441bd4cd-1ff8-4701-a547-d39de3515cf0)

## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
