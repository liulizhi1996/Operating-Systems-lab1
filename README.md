# Operating Systems lab1

This is my lab 1 for Operating System Principles course in XMU. The assignment guide see [Nachos Project Guide] of V22.0202-001 in New York University.

In this lab, I implement a doubly-linked list and try to find all troubles with concurrent programming. 

## Installation
Now, you are in top directory. So, please enter into `threads` directory first.

```
cd threads
```

Compile the project.

```
make depend
make
```

Run the nachos.

```
./nachos -q 2 -t [num_threads] -n [num_items] -e [type_of_error]
```

Command line parameters are:

- `-q 2`: test the doubly-linked list
- `-t`: number of threads
- `-n`: number of items inserted into list by one thread
- `-e`: No. of error

## Acknowledgment
Dasong Chen, Jinbin Tan and Hao Dong assist me to finish this assignment. Thanks for their effort.

[Nachos Project Guide]: http://www.cs.nyu.edu/courses/spring05/V22.0202-001/nachos-labs.pdf