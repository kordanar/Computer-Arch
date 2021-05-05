Computer Architecture final term project
COM-18, Kaiypbekov Arsen
Simple computer simulator
We are going to use an array to simulate computer memory. We can store a number value at each position in the array, and we will use a number value to access each slot in the array (we'll call these array indexes 'memory addresses'). Real computers have memory which can be read and written as individual bytes,
and also in larger or smaller chunks. In real computers memory addresses and values are usually shown as hexadecimal (base-16) form, due to the fact that hexadecimal is a concise alternative to binary, which 'lines up' nicely with
binary: a 1 digit hexadecimal number can represent exactly all of the values which a 4 digit binary number can. However, we are going to represent addresses and values as base-10 numbers (the kind you're used to), so there's one less
thing you need know about at this point. If you like you can read more about binary and hexidecimal numbers here (but it's not essential):  https://jamesfriend.com.au/how-do-binary-and-hexadecimal-numbers-work
Note: could be some bugs
