# 30-3-2020-ASSIGNMENT
<!DOCTYPE html>
<html>
<head>
	<title>Straightforward Calculator</title>
	<meta charset="utf-8"><!-- Encoding-->
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

<style>

a:hover{
    color:rgb(109, 109, 204);
    cursor:pointer;
}
fieldset{
    width:30%;
}

</style>

</head>

<body> 
    <center>
    <table border="1" style="margin-top: 80px;width:30%">
       
        <tr>
            <th>
                <br> 
                <button onclick=myAdd() style="width:152px;font-size: 18px;color:green;border-color:grey;border-radius: 5px;"><a>Click to Add</a></button><br>
                <img src="operators.JPG" style="width:95%;"alt="operators pic">
            </th>
            <th>
                <br> 
                <button onclick=mySub() style="width:152px;font-size: 18px;color:green;border-color:grey;border-radius: 5px;"><a>Click to Subtract</a></button><br>
                <img src="operators.JPG" style="width:95%;"alt="operators pic">
            </th>
        </tr>

        <tr>
            <th>
                <br> 
                <button onclick=myMul() style="width:152px;font-size: 18px;color:green;border-color:grey;border-radius: 5px;"><a>Click to Multiply</a></button><br>
                <img src="operators.JPG" style="width:95%;"alt="operators pic">
            </th>
            <th>
                <br> 
                <button onclick=myDiv() style="width:152px;font-size: 18px;color:green;border-color:grey;border-radius: 5px;"><a>Click to Divide</a></button><br>
                <img src="operators.JPG" style="width:95%;"alt="operators pic">
            </th>
        </tr>
    
    </table>
    </center>

</body>

<script type="text/javascript">
    //Calling functions and performing calculations
    //Addition function
    function myAdd(){
        alert("hi, this is an easy Addition Calculator")
            num1=prompt("enter first number");//Declaring and assigning user's input
            num2=prompt("enter second number");
                num1=parseInt(num1);
                num2=parseInt(num2);//Converting user's input to integer

    function myAdd(num1,num2){
        return num1+num2;//returning the addition of the two numbers entered by the user
    }
    alert("Your answer is: "+myAdd(num1,num2));//displaying the result
    }

    //Subtraction function
    function mySub(){
        alert("Hello, this is an easy Subtraction Calculator")
            num1=prompt("enter first number");//Declaring and assigning user's input
            num2=prompt("enter second number");
                num1=parseInt(num1);
                num2=parseInt(num2);//Converting user's input to integer

    function mySub(num1,num2){
        return num1-num2;//returning the subtraction of the two numbers entered by the user
    }
    alert("Your answer is: "+mySub(num1,num2));//displaying the result
    }

    //Multiplication function
    function myMul(){
        alert("Hello, this is an easy Multiplication Calculator")
            num1=prompt("enter first number");//Declaring and assigning user's input
            num2=prompt("enter second number");
                num1=parseInt(num1);
                num2=parseInt(num2);//Converting user's input to integer

    function myMul(num1,num2){
        return num1*num2;//returning the multiplication of the two numbers entered by the user
    }
    alert("Your answer is: "+myMul(num1,num2));//displaying the result
    }

    //Division function
    function myDiv(){
        alert("Hello, this is an easy Division Calculator")
            num1=prompt("enter first number");//Declaring and assigning user's input
            num2=prompt("enter second number");
                num1=parseInt(num1);
                num2=parseInt(num2);//Converting user's input to integer

    function myDiv(num1,num2){
        return num1/num2;//returning the division of the two numbers entered by the user
    }
    alert("Your answer is: "+myDiv(num1,num2));//displaying the result
    }

</script>
</html>
