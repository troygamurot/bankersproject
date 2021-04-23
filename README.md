# bankersproject

Example output for banker's algorithm program using bankers_medium.txt:

Processing file: 'bankers_medium.txt'...
avail: [ 3  2  4  2]
P#0     3  4  2  1     5  6  7  3     2  2  5  2
P#1     2  2  2  2     3  3  2  2     1  1  0  0
P#2     1  1  0  1     2  3  4  2     1  2  4  1
P#3     2  1  3  0     4  3  5  1     2  2  2  1
P#4     1  2  1  2     2  3  2  3     1  1  1  1
P#5     1  0  0  1     2  1  1  2     1  1  1  1


Banker's algorithm simulation beginning...
--------------------------------------------
avail: [ 3  2  4  2]
P#0     3  4  2  1     5  6  7  3     2  2  5  2
P#1     2  2  2  2     3  3  2  2     1  1  0  0
P#2     1  1  0  1     2  3  4  2     1  2  4  1
P#3     2  1  3  0     4  3  5  1     2  2  2  1
P#4     1  2  1  2     2  3  2  3     1  1  1  1
P#5     1  0  0  1     2  1  1  2     1  1  1  1

<<< Customer thread p#5 started... >>>
REQUEST of  1  1  1  1 for customer 5 request was approved: YES
avail: [ 2  1  3  1]
P#0     3  4  2  1     5  6  7  3     2  2  5  2
P#1     2  2  2  2     3  3  2  2     1  1  0  0
P#2     1  1  0  1     2  3  4  2     1  2  4  1
P#3     2  1  3  0     4  3  5  1     2  2  2  1
P#4     1  2  1  2     2  3  2  3     1  1  1  1
P#5     2  1  1  2     2  1  1  2     0  0  0  0

Customer p#5 has released all resources and is shutting down
<<< Customer thread p#4 started... >>>
REQUEST of  1  1  1  1 for customer 4 request was approved: YES
avail: [ 3  1  3  2]
P#0     3  4  2  1     5  6  7  3     2  2  5  2
P#1     2  2  2  2     3  3  2  2     1  1  0  0
P#2     1  1  0  1     2  3  4  2     1  2  4  1
P#3     2  1  3  0     4  3  5  1     2  2  2  1
P#4     2  3  2  3     2  3  2  3     0  0  0  0
P#5     0  0  0  0     0  0  0  0     0  0  0  0

Customer p#4 has released all resources and is shutting down
avail: [ 5  4  5  5]
P#0     3  4  2  1     5  6  7  3     2  2  5  2
P#1     2  2  2  2     3  3  2  2     1  1  0  0
P#2     1  1  0  1     2  3  4  2     1  2  4  1
P#3     2  1  3  0     4  3  5  1     2  2  2  1
P#4     0  0  0  0     0  0  0  0     0  0  0  0
P#5     0  0  0  0     0  0  0  0     0  0  0  0

<<< Customer thread p#3 started... >>>
REQUEST of  2  2  2  1 for customer 3 request was approved: YES
avail: [ 3  2  3  4]
P#0     3  4  2  1     5  6  7  3     2  2  5  2
P#1     2  2  2  2     3  3  2  2     1  1  0  0
P#2     1  1  0  1     2  3  4  2     1  2  4  1
P#3     4  3  5  1     4  3  5  1     0  0  0  0
P#4     0  0  0  0     0  0  0  0     0  0  0  0
P#5     0  0  0  0     0  0  0  0     0  0  0  0

>>>>>>>>>>>>>>> Customer thread p#4 shutting down... <<<<<<<<<<<<<<<<<