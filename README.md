# Introduction to Bash

## Introduction to the Command Line Interface
What is the command line interface?

Why is it important to learn it?


### Basic Bash Commands
- `cd` - Change the current working 
  ```bash
  cd /path/to/directory
  ```

- `ls` - List the files and directories in the current working directory
  ```bash
  ls
  ```

- `pwd` - Print the current working directory
  ```bash
  pwd
  ```

- `echo` - Print text to the terminal
  ```bash
  echo "Hello, world!"
  ```

- `cat` - Display the contents of a file
  ```bash
  cat filename.txt
  ```


### Bash Scripting Basics
Creating and running a simple script
```bash
#!/bin/bash

# This is a comment
echo "Hello, world!"
```
Save the above script in a file named `hello_world.sh` and run it using `./hello_world.sh`.

## File Manipulation
### Introduction to File Systems and Directories

What is a file system?

What is a directory?

How to navigate directories in Bash?


### File Manipulation Commands
- `touch` - Create a new empty file
  ```bash
  touch filename.txt
  ```

- `mkdir` - Create a new directory
  ```bash
  mkdir dirname
  ```

- `rm` - Delete a file
  ```bash
  rm filename.txt
  ```

- `rmdir` - Delete an empty directory
  ```bash
  rmdir dirname
  ```

- `rm` - Remove non-empty directories
  ```bash
  rm -r dirname
  ```


### Introduction to the Vim Editor

#### What is Vim?
- Vim is a powerful text editor that is available on most Unix-based systems.
- It is designed to be efficient, customizable, and extensible.

#### Why use Vim?
- Vim is lightweight and fast.
- It has a steep learning curve, but once you learn it, you can be much more productive than with a traditional GUI text editor.
- It is highly customizable, so you can create a setup that works best for you.

#### Starting Vim
- To start Vim, open a terminal and type `vim` or `vi`.
- You can specify a file to edit by typing `vim filename.txt`.

#### Modes in Vim
- Vim has different modes for editing text.
- The two main modes are **command** mode and **insert** mode.

#### `Command` Mode
- This is the default mode in Vim.
- In command mode, you can use keyboard shortcuts (also known as "commands") to move around, delete text, and perform other actions.
- Some commonly used commands include:
    - `i` - switch to insert mode
    - `dd` - delete a line
    - `yy` - yank (copy) a line
    - `p` - paste the contents of the clipboard
    - `:w` - save changes to the file
    - `:q` - quit Vim

#### `Insert` Mode
- In insert mode, you can type text into the file.
- To switch to insert mode, press the `i` key.
- To switch back to command mode, press the `Esc` key.

### Basic Text Editing in Vim
- In command mode, you can use keyboard shortcuts to move around, delete text, and perform other actions.

- Here are some basic editing commands:
    - `h` - move cursor left
    - `j` - move cursor down
    - `k` - move cursor up
    - `l` - move cursor right
    - `x` - delete character under cursor
    - `dd` - delete the current line
    - `yy` - yank (copy) the current line
    - `p` - paste the contents of the clipboard
    - `u` - undo the last action
    - `Ctrl + r` - redo the last action 

### Introduction to the Nano Editor
#### What is Nano?
- Nano is a simple, easy-to-use text editor that is available on most Unix-based systems.
- It is designed to be intuitive and user-friendly.

#### Why use Nano?
- Nano is lightweight and fast.
- It is easy to learn and use, making it a good choice for beginners.
- It has many built-in features, such as syntax highlighting and search/replace.

#### Starting Nano
- To start Nano, open a terminal and type `nano`.
- You can specify a file to edit by typing `nano filename.txt`.

#### Basic Text Editing in Nano
- In Nano, you can use the arrow keys to move around the file.

- Here are some basic editing commands:
    - `Ctrl + o` - save changes to the file
    - `Ctrl + x` - exit Nano
    - `Ctrl + k` - cut (delete) the current line
    - `Ctrl + u` - uncut (paste) the last cut line
    - `Ctrl + w` - search for a word or phrase
    - `Ctrl + \` - search and replace a word or phrase

