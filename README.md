Download Link: https://assignmentchef.com/product/solved-sdev425-week6-fixing-c-code-with-vulnerabilities
<br>
In this homework, you will modify an existing C code application that violates several C code rules and recommendations.  Your task is to locate the issues, based on the readings for this course, identify the rule(s) or recommendation(s) being violated and then fix the code. You will discuss each issue in terms of why the issue may cause a security vulnerability, and how you specifically fixed the issue.

<h1>Assignment</h1>

<strong>Review and Understand the Sample C application. </strong>

The current code, developed by a junior developer, has several issues and is not functioning as expected. The desired functionality of the program is to allow a user to select from several choices on a menu. After the user selects the “Exit” option from the menu, the program will populate a password with ‘1’s and then display the value of the password. The program also captures a character so the screen can stay paused for review before exiting. Below are screen shots for a successful program execution.

Unfortunately, not only are there security issues, the code you were provided doesn’t work as expected.

For the first part of this exercise demonstrate your C developer environment is working properly. You can do this by running any of the sample C code applications.

Modify the C code in this example to make the desired functionality work properly. Demonstrate the code works properly through screen captures and describing what changes were made to fix the functionality issues.

<strong>Carefully</strong>, review the code and perform analysis as needed. Consider the following rules and recommendations and hints for items that you might want to review. Note, that some rules and recommendations listed below may not be found as issues in the code.




<ul>

 <li>STR31-C. Guarantee that storage for strings has sufficient space for character data and the null terminator.</li>

 <li>MSC24-C. Do not use deprecated or obsolescent functions.</li>

 <li>FIO34-C. Distinguish between characters read from a file and EOF or WEOF.</li>

 <li>MSC17-C. Finish every set of statements associated with a case label with a break statement.  MSC33-C. Do not pass invalid data to the asctime() function.</li>

 <li>MSC17-C. Finish every set of statements associated with a case label with a break statement.</li>

 <li>DCL20-C. Explicitly specify void when a function accepts no arguments.  MEM30-C. Do not access freed memory.</li>

</ul>

You can use any C compiler you have access to including:

<ol>

 <li>Windows C++ Express or Visual Studio</li>

 <li>Mac X-Code C</li>

 <li>Linux gcc</li>

 <li>VM player with gcc (e.g. SDEV 300 Virtual machine)</li>

</ol>

Be sure you have a C environment where you can compile. Also review those code tutorial links provided in the classroom. Post a note, or contact your professor if you are having significant difficulties compiling a C program.

Once you have your environment working, reviewed and analyzed the code, and determined the rules and recommendations that are violated, you should fix the code. Be sure to document each issue by aligning the rule or recommendation and explain exactly how you fixed the issue.




Hints:

<ol>

 <li>Make sure your C coding environment is working first. Those C tutorials will help you to test your environment.</li>

 <li>Be very careful with the pointers and memory limits of the arrays. Most modern compilers attempt to protect your system resources, but you could potentially produce access violations that could lock your system up. Take your time and review the memory bounds for all of your arrays before you start making code changes</li>

 <li>Start on this early. This will take you longer than you think.</li>

</ol>


