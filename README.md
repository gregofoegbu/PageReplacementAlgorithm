# PageReplacementAlgorithm

This is a page replacement algorithm that implements clock, least recently used and FIFO algorithms 

Run "make" to run

The program should accept input on standard input that first provides the algorithm and number of frames (on the first line), then one page number per line e.g:
FIFO 2<br />
1<br />
2<br />
3<br />
4<br />

For each page number read, it outputs the page number, followed by a F if the access causes a page fault or NF if it does not cause a fault. If there is a page fault, and if that fault evicts an existing resident page, a space is printed, an E and the number of the evicted page on the same line. If you enter an empty string (or we reach End of File for a text file piped to stdin) the program terminates.
