# **Simple Shell Project**

## **simple_shell**

A simple Unix command interpreter.

### **Project Description**
This project is a simpler version of the linux shell. It deals the essential parts that we've learned in C and Linux during the first Trimester with ALX. A user of this simple shell, can run different functionalities that the real shell does.

### **Technologies and Concepts**
C.
Linux (Ubuntu 14.04 LTS).

### **CREATION**
This simple shell was created an Ubuntu 14.04 LTS Operating system, using the C programming language.

### **Compilation**
Go to the project's directory:
cd simple_shell

Compile the repository, this way (you need to have gcc installed on your machine):
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

### **Usage**

You can use the shell in 2 different modes:

- using the shell in an interactive-way:
./hsh you'll get a prompt, then you can start using the shell (Example 1).
- Using the shell in a non-interactive mode:
echo "/bin/ls" | ./hsh (Example 2).

### **The essential Simple Shell Functionalities:**

- Passing Betty (code style checker for holberton C coding standards) checks.
- Displaying a prompt and wait for user input.
- Handling errors.
- Handling commands.
- Handling commands with arguments.
- Handling EOF condition.
- Handling the PATH environment variable.
- Implementing the exit built-in, that exits the shell.
- Implementing the env built-in.

**The functions and system calls that we're allowed to use:**
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- getpid (man 2 getpid)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)

**TEAM MEMBERS**

Team members that contrabuted to this project:

* Simret Mesfin <[Simret Mesfin](https://github.com/simri77)>
* Selamawit Birhanu <[Selamawit Birhanu](https://github.com/Selam25-30)>