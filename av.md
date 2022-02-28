# **Audio / Video Basics**
# **Binary**
## ***Understanding the Latin root:***
* Bi- = Prefix for Two
* -ary = Suffix; A thing which, or pertaining to; connected with; having the character of; apparatus
* Bi-na-ry = A thing which is two
* Binary in it’s simplest term means you have 2 options.  Off or On / 0 or 1

## ***Bit vs. Byte***
A Bit represents one **b**inary dig**it**.  Each Byte represents 8 bits.  Starting with the first bit, the total value for the binary string can only be 0 or 1, that’s 2 options.  Each time you add a bit to the binary string, you double the total number of values.


|Binary Digits|Possible Values|Examples|
| :-: | :-: | :- |
|1|2|0, 1|
|2|4|00, 01, 10, 11|
|3|8|000, 001, 010, 011, 100, 101, 110, 111|
|4|16|0000, 0001, 0010, 0011, 0100, 0101, 0110, etc|
|5|32|00000, 00001, 00010, 00011, 00100, etc|
|6|64|000000, 000001, 000010, 000011, 000100, etc|
|7|128|0000000, 0000001, 0000010, 0000011, etc|
|8|256|00000000, 00000001, 00000010, etc|

This would give you 256 possible options for what a byte can be.  Since 0 is also considered a number, you would get 0 – 255 as the value represented.  Each time you add a bit to a binary string, you add it to the left or the previous numbers.  
## ***Reading Binary***
Please remember that 0 is considered the first number, all values will be literal 0-255. Here is the template for how to figure out a value of a byte sized binary number:


|\_\_\_\_|\_\_\_\_|\_\_\_\_|\_\_\_\_|\_\_\_\_|\_\_\_\_|\_\_\_\_|\_\_\_\_|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|128|64|32|16|8|4|2|1|

You would add the value of each number under the line together to come up with the total value.  We’ll start with the simplest value, 00000001 = 1:

|\_\_0\_\_|\_\_0\_\_|\_\_0\_\_|\_\_0\_\_|\_\_0\_\_|\_\_0\_\_|\_\_0\_\_|\_\_1\_\_|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|128|64|32|16|8|4|2|1|
||||||||1|

Here is a more complicate value, 10101101 = 175:


|\_\_1\_\_|\_\_0\_\_|\_\_1\_\_|\_\_0\_\_|\_\_1\_\_|\_\_1\_\_|\_\_0\_\_|\_\_1\_\_|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|128|64|32|16|8|4|2|1|
|175||47||13|5||1|

Now we’ll look at the largest value possible, 11111111 = 255:

|\_\_1\_\_|\_\_1\_\_|\_\_1\_\_|\_\_1\_\_|\_\_1\_\_|\_\_1\_\_|\_\_1\_\_|\_\_1\_\_|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|128|64|32|16|8|4|2|1|
|255|127|63|31|15|7|3|1|

## ***Base Systems***
Base is a term used to represent how many different values one digit can have in a number system.  For example, the numbering system we use every day is called the decimal system.  Each digit can be from 0-9, giving 10 possible values for each digit.  This would be called a base 10 system.  The base 10 system is believed to be our standard numbering system because we have 10 figures, but other civilizations in the past have used different systems to count.  Binary, with only 2 possible values per digit would be called a base 2 system.  

Standard base systems

|System Name|Base Number|Possible Values|
| :- | :-: | :- |
|Binary|2|<p>0-1</p><p>(0,1)</p>|
|Octal|8|<p>0-7</p><p>(0,1,2,3,4,5,6,7)</p>|
|Decimal|10|<p>0-9</p><p>(0,1,2,3,4,5,6,7,8,9)</p>|
|Hexadecimal|16|0-F (0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F)|
||||

## ***Converting Binary into Hexadecimal***
28 = 2 \* 2 \* 2 \* 2 \* 2 \* 2 \* 2 \* 2 = 256

162 = 16 \* 16 = 256

## ***Standard daily computer usage of Binary and Hexadecimal***

## ***RGB / Color sampling***
Red, Green, and Blue can be combined that different levels to produce different colors.  This is done on a computer by giving each its one byte to represent how much of the color to include.

Pure Red 	= 255,0,0

Pure Green 	= 0,255,0
#
# **Understanding file sizes and abbreviations**

## ***File Size Annotation***

|Byte = B|Bit = b (Binary digIT)|
| :- | :- |
|Kilobyte = KB|Kilobit = Kb|
|Megabyte = MB|Megabit = Mb|
|Gigabyte = GB|Gigabit = Gb|
|Terabyte = TB|Terabit = Tb|


## ***File Size Annotation Values***

**Value	\* 1024		\* 10242		\* 10243**

1 KB	= 1024 B

1 MB	= 1024 KB 	= 1,048,576 B

1 GB 	= 1024 MB	= 1,048,576 KB	=  1,073,741,824 B

1 Byte = 8 bits


