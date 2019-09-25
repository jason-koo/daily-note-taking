# Processes Description and Control
## Suspended Processes
    + suspended means that the process is still on the disk not the memory
    + Blocked means that it is not ready, it still needs an event to occur or its waiting for an event to occur
    + in order to go from blocked/suspend to blocked there needs to be free memory space and if the os believes that      it will be unblocked soon
    + dashed lines in the diagram are not common processes
    + when system creates a new process the os needs to strucutre it and can either store it on the disk or memory
    + 
## Processes and Resources
    + p2 is waiting for the I/O hinted by the dashed line
    + resources are processor, I/O and Main Memory
    + in the diagram it shouldnt say virtual memory instead its just memory
    + 

## Memory Table
    + Used to keep track of both real and secondary(virtual)  memory 
    + manages memory
## Control Tables
### Memory Table
    + Used to keep track of both real and secondary(virtual) memory
    + Manages memory
### Process Table
### I/O tables
### File Table

## Questions
    + P1: blocked for I/O
    + P3: blocked for I/O
    + P5: ready(running cpu, blocked)
    + P7: blcoked for I/O
    + P8: running/ready (suspended)

# Threads
Prcesses have two characteristics:
    + Resource Ownership
        +
    + Scheduling/Execution

## Processes and Thread
    + The unit of dispatching is referred to as a thread or a lightweight process
    + The unit of resource ownership is referred to as a process or task
    + Multithreading - the ability of an OS to support multiple, concurrent paths of execution within a single process
Process - Defined in a multithreaded environment
