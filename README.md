Download Link: https://assignmentchef.com/product/solved-cs207-assignment2
<br>
Provide answers to the following questions:

<ol>

 <li>Convert the following binary numbers to hexadecimal and to decimal:

  <ul>

   <li>10101,</li>

   <li>01</li>

  </ul></li>

</ol>

How many times the decimal answer in (b) is larger than that in (a)? Explain why.

<ol start="2">

 <li>Do the following conversion problems:

  <ul>

   <li>Convert decimal 37.875 to binary.</li>

   <li>Calculate the binary equivalent of 1/7 out to eight places. Then convert from binary to decimal. How close is the result to 1/7?</li>

   <li>Convert the binary result in (b) into hexadecimal. Then convert the result to decimal. Is the answer the same?</li>

  </ul></li>

 <li>Represent the decimal number 7814 in (a) BCD, (b) excess‐3 code, (c) 2421 code, and (d) 6311 code.</li>

 <li>We can perform logical operations on strings of bits by considering each pair of corresponding bits separately (called bitwise operation). Given two eight‐bit strings A = 10110101 and B = 00011100, evaluate the eight‐bit result after the following logical operations: (a) AND (b) OR (c) XOR (d) NOT A (e) NOT B (f) NAND (g) NOR</li>

 <li>Simplify the following Boolean expressions to a minimum or the indicated number of literals:

  <ol>

   <li>(a + b + c’)(a’b’+ c)</li>

   <li>a’b’c + ab’c + abc + a’bc</li>

   <li>(a + c)(a’+ b + c)(a’+ b’+ c)</li>

   <li>A’BD’ + ABC’D’+ ABCD’ to two literals</li>

  </ol></li>

 <li>Given the Boolean functions F1 and F2 , show that

  <ol>

   <li>The Boolean function E = F1 + F2 contains the sum of the minterms of</li>

  </ol></li>

</ol>

F1 and F2

<ol>

 <li>The Boolean function G = F1 ∙ F2 contains only the minterms that are common to F1 and F2 .</li>

</ol>

<ol start="7">

 <li>Convert each of the following to the other canonical form.

  <ol>

   <li>F(x, y, z) = ∑(1, 3, 5, 7)</li>

   <li>F(A, B, C, D) = ∏(3, 5, 8, 11, 13, 15)</li>

  </ol></li>

 <li>Write the following Boolean expressions in:

  <ol>

   <li>(b + d)(a’+ b’+ c)(a + c) SOP form</li>

   <li>a’b + a’c’+ bc POS form</li>

  </ol></li>

 <li>Determine whether the following Boolean equation is true or false.

  <ol>

   <li>y’z’ + yz’ + x’z = x’+ xz</li>

   <li>x’y’+ xz’+ yz = y’z’ + xy + x’z</li>

  </ol></li>

 <li>Simplify the following Boolean functions, using Karnaugh maps:

  <ol>

   <li>F (w, x, y, z) = ∑(11, 12, 13, 14, 15)</li>

   <li>F (w, x, y, z) = ∑(8, 10, 12, 13, 14)</li>

  </ol></li>

 <li>Simplify the following Boolean functions and expressions, using four-variable maps:

  <ol>

   <li>F (A, B, C, D) = ∑ (2, 3, 6, 7, 12, 13, 14)</li>

   <li>F (w, x, y, z) = ∑ (1, 3, 4, 5, 6, 7, 9, 11, 13, 15)</li>

   <li>A’BCD + ABC + CD + B’D</li>

   <li>A’B’C’D’ + BC’D + A’C’D + A’BCD + ACD</li>

  </ol></li>

 <li>Implement the following logical functions with two-level NAND gate circuits.</li>

</ol>

Write down the simplification process.

<ol>

 <li>F(A, B, C, D) = AD + BC’D+ ABC + A’BC’D</li>

 <li>F(A, B, C, D) = A’B’C’D + CD’ + AC’D</li>

 <li>F(A, B, C, D)= (A’+ C’+ D’)(A’+ C’)(C’+ D’)</li>

 <li>F(A, B, C, D) = A’+ AB + B’C + ACD</li>

</ol>

<h1>PART 2: DIGITAL DESIGN LAB</h1>

<h2>INTRODUCTION</h2>

In this lab, you are required to use Vivado 2017.4 and Minisys/EGO1 Practice platform (xilinx FPGA chip artix 7 inside) to design a combinational logic circuit and test it.

<h2>PREAMBLE</h2>

Before working on the coursework itself, you should master the following material.

1.‘Ch2-Boolean Algrebra-ICs-SUSTC.ppt’ and CH3-Minimisation-SUSTC ‘ in Sakai site.

<ol start="2">

 <li>‘Digital design lab6’, ‘Digital design lab7’ and ‘Digital design lab8’ in Sakai site.</li>

 <li>Verilog: http://www.verilog.com</li>

</ol>

<h2>EXERCISE SPECIFICATION</h2>

<strong>TASK1:  </strong>

There are 4 wards, which are numbered from 1 to 4 respectively, among which the #1 ward has the lowest priority, and the #4 has the highest priority (Priority increases as the number increases). Each room has a call bell, it can be turn on and turn off. In the main control room there is a 7-seg tube which shows the ID of the room whose bell is on with the highest priority. Write a circuit to realize this function and test.

<ul>

 <li>Do the design.</li>

 <li>Write testbench to verify the function of your design.</li>

 <li>Create the constraint file.</li>

 <li>Do the synthetic and implementation, generate the bitstream file and program the device, then test on the Minisys/EGO1 develop board.</li>

</ul>




<strong>TASK2:  </strong>

Implement a 4-16 decoder by two 3-8 decoders. You can either modify the provided

3-8 decoder in the or design 74138 decoder

<ul>

 <li>Do the design.</li>

 <li>Write testbench to verify the function of your design.</li>

 <li>Create the constraint file</li>

 <li>Do the synthetic and implementation, generate the bitstream file and program the device, then test on Minisys/EGO1 the develop board</li>

</ul>