# OSShell
An interface that allows users to run commands or executable files

### Overview
 OSShell is a command line interface that searches for the command or executable that the user inputs and spawns a new process that runs that command.

### Compile and Run Instructions
* In Terminal, cd into project directory
* Compile: type `make`
* Run: type `./bin/osshell`

### Usage Instructions
- type into the command line the name of an executable as an absolute path or a relative path, or a command that is accessible from the user's PATH variable
- type `history` to see history of previous commands a positive integer can be added as an argument to limit the number of results. `clear` as an argument sill clear history
- type `exit` to terminate the application
