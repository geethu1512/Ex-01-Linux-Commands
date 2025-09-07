# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

<img width="827" height="92" alt="ls" src="https://github.com/user-attachments/assets/ef6aa5c4-44d8-443d-9ec8-a2c346d32821" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="426" height="138" alt="pwd" src="https://github.com/user-attachments/assets/3d35fa37-3a94-4f28-9509-a8665be6a272" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="358" height="66" alt="mkdir" src="https://github.com/user-attachments/assets/5bf4585e-d580-4d79-9017-58c5533f6bfe" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="390" height="82" alt="rmdir" src="https://github.com/user-attachments/assets/a38e8325-4292-4573-9960-1592f9c7f090" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
<img width="243" height="53" alt="cd" src="https://github.com/user-attachments/assets/234dd267-be22-4580-8de4-ebc3ed700072" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="212" height="167" alt="cat" src="https://github.com/user-attachments/assets/07f5736a-2d00-49cf-8b94-82c50b97e265" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


<img width="367" height="183" alt="cat f2" src="https://github.com/user-attachments/assets/48152306-5d8b-4286-ba43-fb9e43f13e2a" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
<img width="262" height="37" alt="gedit" src="https://github.com/user-attachments/assets/f766d315-6b12-432a-a3de-8fc6b33e86f0" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="308" height="62" alt="su " src="https://github.com/user-attachments/assets/fa8cbfcc-2183-4949-9a5f-703883478da9" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
<img width="283" height="30" alt="mv1" src="https://github.com/user-attachments/assets/216d35d3-1add-4eba-b0e3-610aa2513480" />

 r<img width="291" height="57" alt="mv2" src="https://github.com/user-attachments/assets/d5fc5a49-4c37-4541-9a6e-663659662633" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="318" height="82" alt="rename" src="https://github.com/user-attachments/assets/8ee09e88-a942-41e6-9b1a-aa254bde7da8" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="255" height="402" alt="head" src="https://github.com/user-attachments/assets/303473c7-4900-415a-b546-f101dbebea3a" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 <img width="251" height="190" alt="tail" src="https://github.com/user-attachments/assets/532a6fba-ed27-4926-ae69-d2fd53d57a06" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="657" height="100" alt="id" src="https://github.com/user-attachments/assets/18388519-d061-4708-b113-b21437b3da39" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<img width="260" height="211" alt="grep" src="https://github.com/user-attachments/assets/403dbc4e-c54c-47bc-984e-884825962d29" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="337" height="221" alt="tr" src="https://github.com/user-attachments/assets/55339070-976d-4e92-b0e9-3512c250ce9c" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="421" height="100" alt="chmod" src="https://github.com/user-attachments/assets/8ea9328c-dba8-4656-baa0-b92f774c9c6a" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 <img width="252" height="81" alt="tar" src="https://github.com/user-attachments/assets/c245f1a1-390a-440b-bbe7-775f3c19a3bd" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="426" height="167" alt="chown" src="https://github.com/user-attachments/assets/c81cc8d0-290a-4435-9049-5f81e07fb301" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="137" height="28" alt="mak" src="https://github.com/user-attachments/assets/3ea0fd0e-a334-4e02-b961-a904914b43e9" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="975" height="250" alt="ipconfig" src="https://github.com/user-attachments/assets/7c1a6036-d661-4d10-bff6-c36fc6ffab61" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 <img width="492" height="127" alt="chmod 777" src="https://github.com/user-attachments/assets/f426be03-64fc-4df8-bdc2-e4d35d000f9b" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="322" height="81" alt="gzip" src="https://github.com/user-attachments/assets/cf034adb-d36d-4076-b633-63952c554a23" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 <img width="251" height="158" alt="sort" src="https://github.com/user-attachments/assets/8ac129ce-5d4c-46ce-83c5-218f01f3f671" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="187" height="107" alt="cal" src="https://github.com/user-attachments/assets/5c589e24-bed1-48db-907e-7090ebbf62cd" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="362" height="51" alt="clear" src="https://github.com/user-attachments/assets/a032789f-0391-43f4-aadb-0dfc0e13c440" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 <img width="445" height="35" alt="mail" src="https://github.com/user-attachments/assets/5108df78-8314-45c2-93e9-10be10dfe8f4" />

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="555" height="198" alt="df" src="https://github.com/user-attachments/assets/b95559bb-5ef7-4031-84f9-2bbec6f43e62" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="331" height="56" alt="find" src="https://github.com/user-attachments/assets/5e37154e-b016-49ba-a437-2fdd54e4aa9b" />




















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
