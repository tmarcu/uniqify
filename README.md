uniqify
=======

Uniqify is a program that uses process level parallelism to sort large text files (or files containing text).
Uniqify uses forking to spawn a given number of child processes, which will then take a given file (text preferably),
and sort each word alphabetically, and report the frequency of each word.

Usage:
        uniqify [# of processes] < inputfile
        
        For example, to sort a book from project Gutenberg using 4 processes:
        uniqify 4 < book.txt
