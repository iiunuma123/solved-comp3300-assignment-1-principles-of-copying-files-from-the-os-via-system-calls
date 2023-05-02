Download Link: https://assignmentchef.com/product/solved-comp3300-assignment-1-principles-of-copying-files-from-the-os-via-system-calls
<br>
The aim of this assignment is to help students understand the main principles of copying files from the OS point of view, i.e. via using system-calls. Students will obtain hands on experience in copying files, system-calls, and working with APIs.

<strong>Tasks: </strong>

Section 2.3 of the textbook and Chapter 2 of the class slides describe a program that copies the contents of one file to a destination file. This program works by first prompting the user for the name of the source file and destination files. Write this program using an API of your choice, either Windows API, POSIX API, of Java API; though, I prefer that you use the POSIX API. Make sure you include all necessary error checking, including ensuring that the source file exists.

The system-call sequence for this program (which copies the contents a source file to the destination file) is shown below.

Once you have correctly designed and tested the program, if you used system that supports it, run the program using a utility that traces system-calls. Linux systems provide the <strong><em>strace</em></strong> utility, and Solaris and Mac OS X systems use the <strong><em>dtrace</em></strong> command. As Windows systems do not provide such features, you will have to trace through the Windows version of this program using a debugger (or via the debugger/IDE you are using).


