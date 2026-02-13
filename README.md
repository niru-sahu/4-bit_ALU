# 4-bit_ALU

---

## IMPORTANT POINTS TO NOTE
1) OUTPUTS ARE DISPLAYED IN "HEXADECIMAL" NOT BINARY.  
2) IN CASE OF SUBTRACTION , MSB =1 IS SHOWING POSITIVE SIGN NOT AN MAGNITUDE .
3) FOR SUBTRACTION , LARGER INPUT SHOULD BE GIVEN AT 'A' AND SMALLER AT 'B'.

---

## INSTRUCTIONS TO SIMULATE THE CIRCUIT

1) FOR SUBTRACTION and ADDITION :  
SB = 0  
SA = 0  
for addition : c = 0
for subtraction : c= 1

2) FOR XOR:  
SB  = 0  
SA = 1  

3) FOR LOGICAL AND:  
SB  = 1  
SA = 0  

4) FOR LOGICAL OR:  
SB  = 1  
SA = 1  

---

## This is 4 bit ALU circuit which can perform the following functions:
1) Binary Addition  
2) Binary Subtraction  
3) AND operation  
4) OR operation  
5) XOR Operation 

---

## ➤ FOR BINARY ADDITION
* Here 4 bit binary ripple carry adder is used.  
* For addition C = 0  

---

## ➤ FOR BINARY SUBTRACTION
* CONTROL INPUT (C) is used along with the XOR gates to reverse the input B.  
* For subtraction C= 1  

---

## ➤ ROLE OF IC 74153N (CONTAINS TWO 4:1 MUX)
* Used to choose which operation to be done.  
* We have used 3 such IC (or five 4:1 mux) to make a 4 bit 4:1 mux.

---

## ➤ DISPLAY
* Two hex displays have been used to convert 5 bit binary into hexadecimal.

--

## ➤ AUTHOR : Nirupama Sahu
