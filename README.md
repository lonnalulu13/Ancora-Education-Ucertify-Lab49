# Ancora-Education-Ucertify-Lab49
# Using Shell Features

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=2]

## Objective of the Lab 
In this lab, you will learn to use shell features. Shell in Linux is a text-based interface wherein users can enter command names, execute programs, and manipulate files such as file handles, file permissions, and directories. Tool used Terminal: A terminal, also known as a shell, is a program that allows users to interact with their operating system through a command-line interface. 
## Instructions 
### STEP 1 
From the left sidebar, open the Terminal window. 
### STEP 2 
Execute the following command to display the value of the HOME variable:
```bash
echo $HOME
```
### STEP 3
Execute the following command to display all the shell variables and values:
```bash
set
```
### STEP 4
Execute the following command to display the value of the TEST variable:
```bash
echo $TEST
```
### STEP 5
Execute the following command to change the current shell so that an error message will be displayed when an undefined variable is used:
```bash
set -u
```
### STEP 6
Execute the following command to modify the PATH variable to include the /opt directory:
```bash
PATH="$PATH:/opt"
```
### STEP 7
Execute the following command to create a new environment variable named EVENT and set it to the value "now" by using a single command:
```bash
export EVENT="now"
```
### STEP 8
Execute the following command to display all the environment variables:
```bash
export -p
```
### SEP 9
Execute the following command to create an alias in the current shell for the ls command so it will run the command ls -a:
```bash
alias ls="ls -a"
```
### STEP 10
Execute the following command to display all the aliases for the current shell:
```bash
alias
```
### STEP 11
Execute the following command to remove the fgrep alias from the current shell:
```bash
unalias fgrep
```
### STEP 12
Execute the following command to display a list of previously executed commands:
```bash
history
```
### STEP 13
Re-execute the last !alias command from the history list:
```bash
!alias
```
### STEP 14
Execute the following command to change the maximum number of commands stored in the history list for the current shell to a value of 2000:
```bash
HISTSIZE=2000
```
### STEP 15
Execute the following command to execute the ps -fe command and pipe the output to the less command:
```bash
ps -fe | less
```
### STEP 16
Press q to exit
### STEP 17
Execute the following command to list all filenames in the /etc directory structure (including subdirectories) that are group owned by the root group:
```bash
find /etc -group root -print
```
### CAUTION
* The -print command is optional.
### STEP 18
Execute the following command to display the /etc/passwd file that contain at least three sequential numbers:
```bash
grep '[0-9][0-9][0-9]' /etc/passwd
```
### STEP 19
Execute the following command to display the /etc/passwd file with all occurrences of root replaced with XXXX command:
```bash
sed 's/root/XXXX/g' /etc/passwd
```
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
