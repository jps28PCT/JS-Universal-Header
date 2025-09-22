# JS-Universal-Header
This is a C header and source file containing constants and functions I find myself copy-and-pasting from previous programs I wrote.
I have no idea if this is good coding practice or not, but I am trying to avoid having to rewrite the same functions in different labs and projects.

## Functions:
<details>
  <summary> <h4>int js_Eng_Not(char returnStr[15], double inputNum, int sigFigs)</h4></summary>


This function formats a double number in engineering notation, from yocto- (10<sup>-24</sup>) to yotta- (10<sup>24</sup>). String is 15 chars long, and is always right-justified so the prefix is always the 9th char.

  Passed inputs:
  - `char returnStr[15]`  is the pointer to the string to pass the formatted string back to.
  - `double inputNum`  is the double that is going to be converted to a string in engineering notation
</details>



