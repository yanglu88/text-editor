# text-editor
Text Editor Program in C 
This program works like any text editor with a search and replace function would. Just type in the word you want to look for and the word you wish to replace it with in the command line. 
Also includes wildcard search feature where words inside of a larger word will be replaced. For example: command line -s aga* -r lamp -w
will replace "Off again! On again! In again! Out again!" with "Off lamp! On lamp! In lamp! Out lamp!"
Command line arguments will be parsed and validated for correctness. Program will open, read, write and perform I/O functions only on valid text files.
