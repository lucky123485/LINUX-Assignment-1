                                         **Linux assignment**

 **1.How to make a directory ?**

   The ‘mkdir’ command is used for creating a directory.

 ****

**- Command:**

   **- Example:** mkdir test

**- Describe the command:**

   **- mkdir:** It is used to create a directory

   **-   test:** it is the name of folder

**-Output**

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~$ mkdir test

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~$ ll -ld test

drwxrwxr-x 2 bhavesh bhavesh 4096 Dec 14 12:19 test/

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~$

![](https://lh7-us.googleusercontent.com/EheUA0S3kTlPFN6zc3sJGqyILtpxTOhkT4b6K4PcYXJXZjTo7t8ybOr3QCwAOhMmVUEYLK9zjnKn5bJu8ytVWvhmdOJ2RxV8Y0x2tvIdHg4nMn455Q-gFHff_o2gT2vrCgyzumeS48ZD3FMKOaL8CQk)

**2.Remove a directory**

  To permanently remove a directory in Linux,  we use either the rmdir or rm command

**-Command**

 **-Example:**rmdir

**- Describe the command:**

**-rmdir:**It is used to remove directory

**-test:** it is the folder name 

**-Output**

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~$ rmdir test

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~$

****![](https://lh7-us.googleusercontent.com/HN3vqEYzqLvhGlPn_FtXQiS-oyAcEfzlxUs9NntjfWkiwqf3AvM67QRdrEA58Lre0JQDkNbwSfV5nsTbEyELkdKd6p86pHZD5Rzv6B4xgZpbHkm3_W8r4BIxU6k8dYYGC2Sl-cWnFhKWKV2PVK93wrI)****

**3.Make a copy of a file**

 ****To make a copy of a file in a linux, we can use cp command

**-Command**

 **-Example:**cp

**-Describe the command**

**Mkdir:** I have maintained the above.

**touch:**The `touch` command in Linux is used to create an empty file 

**file.txt:** This is the file name.

**ls:**The `ls` command in Linux is used to list the files and directories in a directory. 

**cp:** This command is used to copy files.

**file.txt:** this is the file name.

**Work:** This is the path of copy file

-**Output**

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ mkdir work

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ ls

work

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ touch file.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ ls

file.txt  work

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ cp file.txt work

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ cd work

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace/work$ ls

file.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace/work$

****![](https://lh7-us.googleusercontent.com/TzyUsdB3NE9vovKjL6Ry85jKhD76wAHt5xjucQS0rGyyzR4uI0_vQ1sbOs9akwd3ODFFVhKbEenFhigISYbI97NHjy_RJIGbfevRV2YpBxARkTlPsCqwEWBBKCJ6NC15k6mOy0wtfJgA-Xj0H0TZwCA)****

**4.Move or rename a file**

In Linux, you can use the `mv` command to move or rename files and directories. 

**-Command**

**-Example:**mv

-**Describe the command**

**touch:** I have maintained the above command.

**ls:**  The ‘ls’ command  is used to list files and directories in a directory.

**mv:** Here mv command is used to rename a file name.

**file1**.txt:This is the name of the file.

**file2.txt**: This is the name of the new file.

**mv:** Here this command is used to move a file to directory

**file2.txt:** This is the name of the file.

**Bhavesh**: This is the name of the directory in which move the file.

-**Output**

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ mkdir bhavesh && touch file1.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ ls

bhavesh  file1.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ mv file1.txt file2.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ ls

bhavesh  file2.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ mv file2.txt bhavesh/

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ ls bhavesh/

file2.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$

![](https://lh7-us.googleusercontent.com/lTizvSTx9klByA5bc9FLjuQOa3Af3yfS_MetQDGlBFca1lmmPbFFXietC2KJUUSMZ_wuiF0RdQ6Rk36d_M_oUmdZ6uE1Z57ngH4ru_j6HLJvjLdDCLSSdybUjCWtD4EL0QKf99GY4PiM_8qzh972fPI)

\
\


**5.Create an empty file**

 Touch command is used to create an empty file.

**-Command**

 **-Example**:touch

**-Describe the command**

**-touch:** this command is used to create the file

**-lucky.txt:** This is the name of file which we create

**-Output**

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ touch lucky.txt

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ ls

lucky.txt

![](https://lh7-us.googleusercontent.com/BZ5RoRgfZJgoUGqeD-AID784b49IgIzXkbiOABR5ERjhCtdtsBDYUjWnMF7uSMaB1GVsZUBIRvUSYSeV8P8MICRn4S-59CUuT2gA9UB8ESkL1tjM233J04pyaOV-dqbGnYkft5AzJBmbGcpK4bX2BuQ)

 **6.Remove multiple files with a single command**

  **In Linux, we can use the rm command to remove (delete) files.** 

**-Command**

**-Example:**rm

**-Describe the command**

**touch:** I have already mentioned above.

**rm** : this command is used to remove files.

**ls**: I have already maintained the above.

**-Output**

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace/bhavesh1$ touch exp1.txt exp2.txt exp3.txtbhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace/bhavesh1$ lsexp1.txt  exp2.txt  exp3.txtbhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace/bhavesh1$ rm exp1.txt exp2.txtbhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace/bhavesh1$ lsexp3.txt

![](https://lh7-us.googleusercontent.com/jdjP_CagmoAJP7afVkQBKQBwQZDtg2gDBgshRBu1V-0IQ6xyqS7aJLBwn8uHWJsYzsMI-KeS4R8RxBZLD3kHBNhxbCU6NLsP7hUXRiVAYcbp3GlBbg4ltsQ0yUOX7m_Aqgh2cDrnR3j8m3J9Xz5G8I0)

**7.Remove content from the folder without removing folder**

To remove the contents of a folder without removing the folder itself, use the command rm -r /path/to/main\_directory/\*.-

**Command-**

**-Example:**rm -r

**-Describe the command**

**Mkdir**:I have maintained the above but a b c .. my directory.

**touch**:I have maintained the above but 1 2 3 4 .. my file.

**ls**: I have maintained the above.

**Pwd**: print the full path of the current working directory.

**cd** : cd command is used to change the current working directory and ‘a’ is the name of the directory.

**rm**: rm stands for remove.

-**r:** Stands for "recursive" meaning it will delete directories and their contents.

**/home/bhavesh/workspace/\***:Specifies the path to the directory you want to operate on.

****![](https://lh7-us.googleusercontent.com/0Pgq1VRveNGX3xOzgFkbI-vWGdb478B_AqM53UrWJ-TSSTmn9BRDyjeEcn0TFbNYTs6IiQv4zp6MbGmptLpOrlZLRCW1-bcGXPUUmU7uLQvInSdTMWWZceAw2jF8GvMDSCkxSJGWvS8uVPsNV4kF1bg)****

**8.Create multiple folders(a-z) with a single command.**

“Mkdir {a..z}” command is used to create multiple directories with a single command. 

**command-**

**Example:-**mkdir {a..z}

**-Describe the command**

**-mkdir {a..z}:**This command utilises brace expansion to create folders from a to z. Each letter is separated by ... This will create folders named a, b, c, ..., z in the current directory.

**-Output**

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ mkdir {a..z}

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$ ls

a  b  c  d  e  f  g  h  i  j  k  l  m  n  o  p  q  r  s  t  u  v  w  x  y  z

bhavesh\@bhavesh-HP-Laptop-15-da1xxx:\~/workspace$

****![](https://lh7-us.googleusercontent.com/0RXrzwWEvRcwJZ9NjEkXT1HyNtG0tX4w7unvY26yMY_PXXZScfKk39pgn9Z5pOoYWq0roclQIIFCYmNv2DA3erx4dzEE-bSo38iAaPiUVmluftc6dx81KszRqBdHoIlsiNinY_N9oHhVUsVIFHsleuw)****

\
\
\
\


\-
