---
title: Windows Command Interpreter
category: CLI
updated: 2019-05-22
---

<!---
### Template
```bash
# DESCRIPTION:

# EXAMPLE:

```
--->
### Help

```bash
# Help gets available commands, or displays help info for commands

help
/?

# Example
shutdown Help
shutdown /?

```

### Echo
```bash
# DESCRIPTION: Prints the following info to STDOUT
echo
# EXAMPLE:
echo hello world
```

### Type
```bash
# DESCRIPTION: Prints file contents to STDOUT
type
# EXAMPLE:
type file.txt
```

### Redirects
```bash
# DESCRIPTION: Redirects can be used to either send std data in or out.

# EXAMPLES:
# Sends output of command to text file
command > filename.txt
# Sends output of command to text file while appending to the original file contents
command >> filename.txt
# Types filename out and sends into command
command < filename.txt
# Sends error message output of command to text file
command 2> filename.txt

```

### Pipes
```bash
# DESCRIPTION: Takes the output of one command and pipes it into another command.
|
# EXAMPLE:
command1 | command2

```

### Display System info
```bash
# DESCRIPTION: The following commands will display different pieces of systems information.

# EXAMPLE:
hostname # Displays hostname of current machine
ver # Displays Windows version
vol # Displays disk volume label and serial number
systeminfo # config information for local machine. Can be used on remote machines
```

### Set
```bash
# DESCRIPTION: Used to managed system variables

# EXAMPLE:
set z=hello world
set z = hello world # using this variant makes your variable %z % instead of %z%
```

### CD
```bash
# DESCRIPTION: Change your directory.

# EXAMPLE:
cd c:\windows\system32
cd ..\.. # this will return you back two folders instead of one.
```

### Template
```bash
# DESCRIPTION:

# EXAMPLE:

```

### Template
```bash
# DESCRIPTION:

# EXAMPLE:

```
