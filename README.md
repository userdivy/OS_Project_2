# OS_Project_2

Elevator Simulation

This project introduces you to the nuts and bolts of system calls, kernel programming, concurrency, and synchronization in the kernel.

How to compile-
=================

run make command
insert the module using sudo insmod elevator.ko
print out the proc file using cat /proc/elevator or watch -n1 cat /proc/elevator
issue systems calls using the consumer.c and produce.c files from Canvas under the Testing folder
remove the module using sudo rmmod elevator

Group members-
=================

Divya Lakshmi Varampati

Nadhan Yamala


Division of Labor:
=================

Nadhan Yamala: Struct for elevator status (for proc file use), Move the elevator based on the state,Function for removing all passengers (elevator
	             and waiting) used by module exit, 

Divya Lakshmi: System Calls, Return passenger unit based off passenger type, Return passenger weight based off passenger type,Free up memory allocated for.                       'message when proc file is removed, Testing, Readme, MakeFile, 


File Details
================

main.c: Contains the main method for using the program

MakeFile : all the make commonds to compile, execute and clean

