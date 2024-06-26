# Linux-Shell-Development
A linux SHELL in C++ with key OS features like IO redirection, external script execution, pattern matching and malware detection.

This project is an implementation of a shell that runs as an application program on top of the Linux kernel. The shell accepts user commands (one line at a time) and executes them much like the default linux bash terminal.
The following features have been implemented:

- Run an external command
- Run an external command by redirecting standard input/ output from/ to a file
- Combination of input and output redirection
- Run an external command in the background with possible input and output redirections
- Run several external commands in the pipe mode along with input and output redirections
- Interrupting commands running in your shell (Ctrl-C)
- Move a command in execution to the background (Ctrl-Z)
- Implementing cd and pwd
- Handling wildcards in commands (* and ?)
- Implementing searching through history using up/down arrow keys
- Implementing cursor movement using left/right arrow keys
- Cursor moves to start/end of line using Ctrl+A and Ctrl+E

I have tried to keep the shell as close to the bash terminal as possible, so the syntax of these commands are similar to their bash counterparts.
