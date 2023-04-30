Download Link: https://assignmentchef.com/product/solved-cs2310-lab-8-functions
<br>
Please test the correctness of your programs in Q1, Q2a, Q2b, and Q3 using PASS.

<strong>Q1.</strong> Download calc.cpp. Complete the function definitions such that it computes addition, subtraction, multiplication, and division of two real numbers.

Output the result in 2 decimal places. Example inputs and outputs are as follows.

<strong><u>Expected Outputs:</u> </strong>




<table width="0">

 <tbody>

  <tr>

   <td width="282"><strong>Example-1 </strong></td>

   <td width="288"><strong>Example-2 </strong></td>

  </tr>

  <tr>

   <td width="282">Enter an Expression consist of two operands and one operator. <strong><u>1+2</u></strong>3.00</td>

   <td width="288">Enter an Expression consist of two operands and one operator.<strong>2.5-1 </strong>1.50</td>

  </tr>

  <tr>

   <td width="282"><strong>Example-3</strong></td>

   <td width="288"><strong>Example-4</strong></td>

  </tr>

  <tr>

   <td width="282">Enter an Expression consist of two operands and one operator. <strong><u>2*3</u></strong>6.00</td>

   <td width="288">Enter an Expression consist of two operands and one operator. </td>

  </tr>

  <tr>

   <td width="282"><strong>Example-5</strong></td>

   <td width="288"><strong>Example-6</strong></td>

  </tr>

  <tr>

   <td width="282">Enter an Expression consist of two operands and one operator. <strong><u>1-2.5</u></strong>-1.50</td>

   <td width="288">Enter an Expression consist of two operands and one operator. </td>

  </tr>

 </tbody>

</table>




<strong>Q2a.</strong> Download and complete the program printNum.cpp, which intends to print integers in English, corresponding to user input <em>(range: 1 to 19). </em>




The program consists of the following functions:  <strong>print1to9</strong>: accepts an integer from 1 to 9 as input and print the number in English. This function has been defined for you.<em> (but not 100% correct !!)</em>




Let’s fix the bug(s) in function <strong>print1to9</strong>. After that, you create another function called <strong>print10to19</strong>. The function accepts an integer from 10 to 19 as input and prints the number in English.




The user input should be done in the main function. After the number is read, the appropriate functions should be called for output.




<strong><u>Expected Outputs:</u> </strong>




<table width="0">

 <tbody>

  <tr>

   <td width="276"><strong>Example-1</strong></td>

   <td width="294"><strong>Example-2 </strong></td>

  </tr>

  <tr>

   <td width="276">Enter a number in Range [1–19].<strong><u>0</u></strong>0 is not in range from 1 to 19</td>

   <td width="294">Enter a number in Range [1–19]. <strong><u>20</u> </strong>20 is not in range from 1 to 19</td>

  </tr>

  <tr>

   <td width="276"><strong>Example-3</strong></td>

   <td width="294"><strong>Example-4</strong></td>

  </tr>

  <tr>

   <td width="276">Enter a number in Range [1–19].<strong><u>4</u></strong>Four</td>

   <td width="294">Enter a number in Range [1–19]. <strong><u>15</u> </strong>Fifteen</td>

  </tr>

 </tbody>

</table>







<strong>Q2b.</strong> Modify the program in Q2a such that it accepts an integer (1 to 99) from the user and prints the English representation accordingly.




You should define an extra function as follows.

<strong>print20to99</strong>: accepts an integer from 20 to 99 as input and print the number in English.




(<em>Hint: You may break down the number into units digit and tens digit and call the </em><strong><em>print1to9</em></strong><em> and </em><strong><em>print10to19</em></strong><em> functions you defined in Q2a to generate the output.</em>)




Similar to Q2a, the user input should be done in the main function. After the number is read, the appropriate function(s) should be called for printing the result.




<strong><u>Expected Outputs:</u> </strong>




<table width="0">

 <tbody>

  <tr>

   <td width="276"><strong>Example-1</strong></td>

   <td width="294"><strong>Example-2 </strong></td>

  </tr>

  <tr>

   <td width="276">Enter a number in Range [1–99].<strong><u>0</u></strong>0 is not in range from 1 to 99</td>

   <td width="294">Enter a number in Range [1–99]. <strong><u>20</u> </strong>Twenty </td>

  </tr>

  <tr>

   <td width="276"><strong>Example-3</strong></td>

   <td width="294"><strong>Example-4</strong></td>

  </tr>

  <tr>

   <td width="276">Enter a number in Range [1–99].<strong><u>21</u></strong>Twenty One </td>

   <td width="294">Enter a number in Range [1–99]. <strong><u>-21</u> </strong>-21 is not in range from 1 to 99</td>

  </tr>

  <tr>

   <td width="276"><strong>Example-5</strong></td>

   <td width="294"><strong>Example-6</strong></td>

  </tr>

  <tr>

   <td width="276">Enter a number in Range [1–99].<strong><u>78</u></strong>Seventy Eight</td>

   <td width="294">Enter a number in Range [1–99]. <strong><u>100</u> </strong>100 is not in range from 1 to 99</td>

  </tr>

 </tbody>

</table>

<strong>Q3.</strong> Download <strong>sortArray.cpp</strong>. The program intends to use bubble sort to arrange the numbers in array <strong>Num[]</strong> in an ascending order. As in typical bubble sort, the program compares number pairs repeatedly and it swaps the numbers if they’re placed out-of-order.




Your task is as follows:

− Complete the <strong>Swap()</strong> function which exchanges the values of two integers using pass-byreference.




− Complete the bubble sort by filling out correct indices in the two for loops for array elements.




<strong><u>Expected Outputs:</u> </strong>




<table width="0">

 <tbody>

  <tr>

   <td width="276"><strong>Example-1</strong></td>

   <td width="294"><strong>Example-2 </strong></td>

  </tr>

  <tr>

   <td width="276">Enter 10 numbers:<strong><u>1 3 2 5 4 7 6 8 9 10</u></strong>The sorted numbers:1 2 3 4 5 6 7 8 9 10</td>

   <td width="294">Enter 10 numbers:<strong><u>1 2 3 4 5 6 7 8 9 10</u></strong>The sorted numbers:1 2 3 4 5 6 7 8 9 10</td>

  </tr>

  <tr>

   <td width="276"><strong>Example-3</strong></td>

   <td width="294"><strong>Example-4</strong></td>

  </tr>

  <tr>

   <td width="276">Enter 10 numbers:<strong><u>10 9 8 7 6 5 4 3 2 1</u></strong>The sorted numbers:1 2 3 4 5 6 7 8 9 10</td>

   <td width="294">Enter 10 numbers:<strong><u>3 44 38 5 47 15 36 26 27 2</u></strong>The sorted numbers:2 3 5 15 26 27 36 38 44 47</td>

  </tr>

 </tbody>

</table>




Interested students may also modify the program such that the elements are sorted in descending order, rather than ascending. (Note: No need to upload this program to PASS)


