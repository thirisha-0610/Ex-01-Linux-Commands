
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

<img width="680" height="149" alt="594046636-907387f8-3f4f-4992-b7d0-3465d37088f6" src="https://github.com/user-attachments/assets/f3fb3851-1312-42f3-9b14-983b5392e627" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


 <img width="612" height="45" alt="594046846-2719f7d2-ed47-4ea5-aab0-f5686e8b39fe" src="https://github.com/user-attachments/assets/40dd8f34-3a6a-4b03-89a7-16b934ffa488" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="603" height="39" alt="594047029-430f8e2a-b7cb-4651-9964-01a9eb18b738" src="https://github.com/user-attachments/assets/fa1d08cc-52aa-4cd6-b8c7-66c8c7ad8a9a" />



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>




<img width="608" height="41" alt="594047135-f891babc-523d-4673-a3ec-d20ac923416d" src="https://github.com/user-attachments/assets/614d7c6f-efbc-4db7-a7df-154bd075b327" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


 <img width="610" height="45" alt="594047293-2f142c79-f4b5-480c-a1fd-0e767ffcf540" src="https://github.com/user-attachments/assets/f761ef33-27c0-43eb-97ab-8e13edbf7a75" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


<img width="624" height="75" alt="594047392-c6ecafc8-6d8a-4b6b-89f2-3fd68af439cc" src="https://github.com/user-attachments/assets/96c743d4-de94-40a4-8317-fbc95042b28a" />


### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="607" height="44" alt="594047491-8583d470-2533-4277-88b6-d871747ada68" src="https://github.com/user-attachments/assets/a643782b-54fb-4d23-a635-79e0955d2d03" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name



<img width="645" height="21" alt="594047573-6fef5286-ef39-4d76-bc7e-c4b33400e2de" src="https://github.com/user-attachments/assets/ac052cff-bac9-46d9-be6e-1e16861b9821" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>



<img width="622" height="67" alt="594047648-a642b39c-63f2-4e1d-9406-54b032689636" src="https://github.com/user-attachments/assets/19da8d30-58b2-4451-8338-6fe59bd3905f" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>


<img width="622" height="67" alt="594047648-a642b39c-63f2-4e1d-9406-54b032689636" src="https://github.com/user-attachments/assets/4ef94c85-9e60-4929-a8c4-6f8e75f1c70f" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


<img width="684" height="166" alt="594047950-a0231ac7-8e73-4c28-a3c4-ee4320bea215" src="https://github.com/user-attachments/assets/cfe09188-751d-4971-8308-4d518a068d7f" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>



<img width="612" height="201" alt="594048063-249a87dd-1c16-42d3-ae36-e41063e521d8" src="https://github.com/user-attachments/assets/9c580f60-35f4-4190-a08c-4daa1d8c3049" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>



 <img width="474" height="202" alt="594048182-4fea3e04-dc25-48b3-9805-66c1d1a185e5" src="https://github.com/user-attachments/assets/b7f06d3c-b253-4ebc-9d37-6c90cb92fadb" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


<img width="726" height="78" alt="594048258-cf21e70c-0c18-4dfb-b6fa-ff9461c2cdd9" src="https://github.com/user-attachments/assets/d53af4fa-951e-45fd-b505-62b2ee4c0b65" />

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>



<img width="622" height="41" alt="594048395-b4e4d32b-e9dd-49d3-8a33-cd2b3a11427c" src="https://github.com/user-attachments/assets/29fe7a31-f372-4ebb-87b7-986cfc30bcb2" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


<img width="707" height="128" alt="594048455-dedfc112-23b7-4fb1-a6c6-a3db16e5cdda" src="https://github.com/user-attachments/assets/21037f4f-08d2-497e-89b5-97ea2a1a33e3" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>



### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="579" height="199" alt="594048808-59724f6c-9b05-4e56-a016-b7e4f7724f4c" src="https://github.com/user-attachments/assets/f92d3e60-b0d0-4fe3-965c-0b0eed6e31b5" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name



### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


<img width="679" height="59" alt="594048911-f2e3a221-dbf6-4503-812f-225dcbb85d34" src="https://github.com/user-attachments/assets/5042328e-8b7c-44f0-9e14-9d9469ed86cf" />

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="874" height="178" alt="594048979-e8afebad-444a-4ac6-ab5a-e56cccb0f8e9" src="https://github.com/user-attachments/assets/9b05b6c6-0040-401e-b8ff-ae5c7f41acf6" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="647" height="38" alt="594049146-34de28d2-f2ec-4c7d-b2b2-0630dace7aaa" src="https://github.com/user-attachments/assets/3f3fd1da-514f-46df-8fa4-42814a6ea737" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>




### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="696" height="187" alt="594049242-ba982377-da31-40fd-90c8-76c41e23458a" src="https://github.com/user-attachments/assets/f7274f90-af03-4875-865e-63eee18eef79" />



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


<img width="692" height="131" alt="594049341-1374d4ba-3ae4-4cbb-a2d0-c263b82a8a08" src="https://github.com/user-attachments/assets/7be1a052-f4d8-49cd-92ff-1eae79cd5131" />


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="627" height="161" alt="594049418-943afd30-7dcb-478b-b613-4555eaa3c546" src="https://github.com/user-attachments/assets/5507d798-a82a-441d-96dc-c4b6ad65f374" />



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="704" height="186" alt="594049481-c27d5bf3-0252-4311-a40a-8e2c93150cc5" src="https://github.com/user-attachments/assets/8533104b-f0c8-47ca-96aa-a47ea7fbfcbd" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>



 <img width="858" height="81" alt="594049564-65f5a351-47a9-4efd-9923-387262c8105e" src="https://github.com/user-attachments/assets/1a11f0bd-b70f-4574-aa6f-188e9beb2259" />

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="730" height="238" alt="594049630-18fe4fff-a91a-448d-90ca-f757e18acd3e" src="https://github.com/user-attachments/assets/3778682e-9f09-419b-8d91-53e906e8f696" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”



# RESULT:


Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
