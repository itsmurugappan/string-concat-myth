# String Concat Myth Test 

When concatenating strings it was always recommended to use String buffer, then later String Builder. I also did the same whenever i
needed to but after watching a video by Dr. Venkat Subramaniam now i would check how the compiler internally does before using builder 
or buffer. 
Please take a look at the StringConcatMythTest.java file and check the class file for the same 
You would notice Java compiler internally using a String builder for concatenation and 
when adding string in the same line like "hi" + "george" it would just create one string.

![](./String to Stringbuilder.jpg)

