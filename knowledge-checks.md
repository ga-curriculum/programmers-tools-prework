## Command Line Interface

### Knowledge Check

How would you find out which directory your terminal “is in”?

Select the best answer.

- Incorrect: `cd -a`

- Incorrect : `ls ~`

- Incorrect: `cwd`

- Correct : `pwd`

Correct: `pwd` is short for 'print working directory', which lists the content of the directory the terminal is currently 'in'.

### Knowledge Check

Which of the following is the most comprehensive way of removing a directory named `sales` from your home directory?

Select the best answer.

- Incorrect: `rm sales`

- Correct: `rm -r ~/sales`

- Incorrect: `delete sales`

- Incorrect: `rm -r Parent directory`

Correct: We use the `rm` command with `-r` to recursively remove directories, and point to the home folder with a `~`, which correctly references the home folder across both system types (Mac, Linux, etc)

### Knowledge Check

Assuming `Documents` is a directory located within the working directory of the terminal, what does the command `ls -a Documents` do?

Select the best answer.

- Changes into the Documents directory and lists all contents
- (Correct): Remains in the current directory and lists all contents of the Documents directory
- Remains in the current directory and lists only the non-hidden contents of the Documents directory
- Changes into the Documents directory and lists its non-hidden contents

Correct:The `ls -a` command lists both the hidden and non-hidden contents of the `Documents` directory while staying in the current directory.
