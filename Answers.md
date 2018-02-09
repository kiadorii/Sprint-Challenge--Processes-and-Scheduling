I'm not 100% certain about my answers #4
1.  Answer: B
    The possible range spaces that each process can have from a 32KB of memory is 0 - 64,000. This means that once the two processes were initialized, they were given a range from 0 - 64,000.

2. The possible states are: Created, Ready, Running, Blocked, and Terminated.
    Created: It is when a process is created
    Ready: It has been an address in the memory and can be executed
    Running: In the process of it be executed
    Blocked: When the process comes to a point where it needs another 'authority' to continue
    Terminated: This is when the process has completed and/or it has been killed.

3.  write - 4368.9534898ns
    printf - 1037.846069ns

4. `printf` may run faster than `write` because it does not have to make as many calls as write. Write is a system call that writes out of a buffer.