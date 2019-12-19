# os2
test

getChild:

this system call gets PID of a process and returns process ids of its children.when the process has more than on child,this system call
should return a multi-digit number.and the order does not matter in this multi-digit number.for example,suppose your current process has
two children andthe first childand the second have PID 6 and 7,respectively.this system call should return 67 or 76 as an output.for 
adding this system call,first, you should add getppid system call.this system call return PID of the parent process.

whrite a user-level program named getChildTest for testing your implementation.first, creat a number of children by using fork().then,
for each process, you should print PID ,PPID,and the outputof the getChild system call with the parent PID as an argument.
