# ITA1414-Ethical-Hacking
# Experiment 1: Basic Linux File and Directory Management

## Aim
To learn and practice basic Linux commands for creating, viewing, editing, renaming, deleting, and managing files and directories in Kali Linux.

---

## Objective

The objective of this experiment is to become familiar with essential Linux terminal commands used for file and directory management. These commands form the foundation for ethical hacking, penetration testing, and Linux system administration.

---

## Software Requirements

- Oracle VirtualBox
- Kali Linux 2025.4
- Bash Terminal

---

## Commands Used

| Command | Description |
|----------|-------------|
| `ls` | Lists files and directories |
| `ll` | Displays detailed file information |
| `tree` | Shows directory structure in tree format |
| `users` | Displays logged-in users |
| `vim` | Creates or edits files |
| `less` | Displays file content page by page |
| `head` | Displays first 10 lines of a file |
| `tail` | Displays last 10 lines of a file |
| `mkdir` | Creates a new directory |
| `rm` | Deletes files |
| `mv` | Renames or moves files |
| `uptime` | Shows system uptime and load average |
| `date` | Displays current system date and time |

---

## Procedure

1. Open Kali Linux Terminal.
2. Navigate to the working directory.
3. Create text files using `vim`.
4. Display file contents using `less`.
5. List files using `ls` and `ll`.
6. Create directories using `mkdir`.
7. Rename files using `mv`.
8. Delete unwanted files using `rm`.
9. View the directory structure using `tree`.
10. Display the first and last lines of a file using `head` and `tail`.
11. Check system information using `uptime` and `date`.

---

## Commands Executed

```bash
ls
ll
vim test1.txt
vim Pranav.txt
less Pranav.txt
mkdir New_directory
tree
head numbers.txt
tail numbers.txt
mv test1.txt sample.txt
rm test2.txt
users
uptime
date
