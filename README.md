# calculator
<!DOCTYPE html>
<html>
<body>
	<table >
		<tr style="background-color: black;">
			<td colspan="4"> <form name="calculator" >
				              <input type="text" name="answer" size="40" style="height:50px;"/><br></td>
		</tr>
		<tr>
			<td colspan="2"><input type="button" style="height:60px; width:150px" value="C" onclick="calculator.answer.value = ''"/></td>
			<td><input type="button" style="height:60px; width:60px"value="<-" onclick="calculator.answer.value = ' '"/></td>
			<td style="background-color: brown"><input type="button" style="height:60px; width:60px" value="/" onclick="calculator.answer.value += '/'"/></td>
		</tr>
		<tr>
			<td><input type="button" style="height:60px; width:60px" value="7" onclick="calculator.answer.value += '7'"/></td>
			<td><input type="button" style="height:60px; width:60px" value="8" onclick="calculator.answer.value += '8'"/></td>
			<td><input type="button" style="height:60px; width:60px" value="9" onclick="calculator.answer.value += '9'"/></td>
			<td style="background-color: brown;"><input type="button" style="height:60px; width:60px" value="*" onclick="calculator.answer.value += '*'"/></td>
			
		</tr>
		<tr>
			<td><input type="button" style="height:60px; width:60px" value="4" onclick="calculator.answer.value += '4'"/></td>
			<td><input type="button" style="height:60px; width:60px" value="5" onclick="calculator.answer.value += '5'"/></td>
			<td><input type="button" style="height:60px; width:60px" value="6" onclick="calculator.answer.value += '6'"/></td>
			<td style="background-color: brown;"><input type="button" style="height:60px; width:60px"value="-" onclick="calculator.answer.value += '-'"/></td>
		</tr>
		<tr>
			<td><input type="button" style="height:60px; width:60px" value="1" onclick="calculator.answer.value += '1'"/></td>
			<td><input type="button" style="height:60px; width:60px" value="2" onclick="calculator.answer.value += '2'"/></td>
			<td><input type="button" style="height:60px; width:60px" value="3" onclick="calculator.answer.value += '3'"/></td>
			<td style="background-color: brown;"><input type="button" style="height:60px; width:60px" value="+" onclick="calculator.answer.value += '+'"/></td>
		</tr>
		<tr>
			<td colspan="3"><input type="button" style="height:60px; width:250px" value="0" onclick="calculator.answer.value += '0'"/></td>
			<td style="background-color: brown;"><input type="button" style="height:60px; width:60px"value=" = " onclick="calculator.answer.value = eval(calculator.answer.value)" />
		</tr>
	</table>

</body>
</html>
<style>
	table, th, td{ border: 1px solid black;
	               border-collapse: collapse; }
	 table { height: 400px;
	         width: 200px;}
	 td { padding: 15px; }         
	table{ background-color: silver; } 
	table { font-family: arial.verdana.sans.serif;
	          font-size: 50px;} 

</style>
