####  Day 1 – Linux Basic Navigation Commands
#####################
Author: Madhav Jha  
Date: 01 August 2025
####################

-------------------

#####  Navigation Commands in Linux

| Command         | Description |
|-----------------|-------------|
| pwd           | Shows the current working directory (Print Working Directory). |
| ls            | Lists files and directories in the current directory. |
| ls -l         | Lists in long format with file permissions, ownership, size, etc. |
| ls -a         | Lists all files including hidden ones (those starting with .). |
| cd ~          | Moves to the home directory. |
| cd /          | Moves to the root directory. |
| cd ..         | Moves one directory up (parent directory). |
| cd directory  | Changes current directory to "directory". |
| clear         | Clears the terminal screen. |

--------------------------
___
##  Example Session

```bash
pwd
/home/ubuntu

ls -l
total 4
-rw-r--r-- 1 ubuntu ubuntu  0 Jul 31 10:00 file.txt
drwxr-xr-x 2 ubuntu ubuntu 4096 Jul 31 10:00 dir1/

cd dir1
pwd
/home/ubuntu/dir1

