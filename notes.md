# Truffula Notes
As part of Wave 0, please fill out notes for each of the below files. They are in the order I recommend you go through them. A few bullet points for each file is enough. You don't need to have a perfect understanding of everything, but you should work to gain an idea of how the project is structured and what you'll need to implement. Note that there are programming techniques used here that we have not covered in class! You will need to do some light research around things like enums and and `java.io.File`.

PLEASE MAKE FREQUENT COMMITS AS YOU FILL OUT THIS FILE.

## App.java
S: This is where the main application is. It includes comments on how the app will be used and what its output should be. I will be implementing TruffulaOptions, passing it to a printer, then printing the output by calling printTree.
Q: 

## ConsoleColor.java
S: This is where ANSI colors can be found to be applied to certain text in the console. I will implement returning the ANSI code associated as color, then the code as a string.
Q: How do I choose colors appropriatley to aid in accessibility?

## ColorPrinter.java / ColorPrinterTest.java
S: This is where we can set the color of text output using ANSI escape codes. These colors will be managed using ConsoleColor. I will be implementing how colors are set or reset depending on if it is a message or newline.
Q:

## TruffulaOptions.java / TruffulaOptionsTest.java
S: This is how the user can configure different options in the directory tree such as showing hidden files, using colored output, and where the root directory will begin to print the tree.
Q:

## TruffulaPrinter.java / TruffulaPrinterTest.java
S: This is how the directory tree structure will be printed, supporting option colored output, sorted files and directories case insensitive, and cycling through colors.
Q:

## AlphabeticalFileSorter.java
S: This class takes the names of files, puts them in an array, and sorts them alphabetically, ignoring case differences. 
Q: