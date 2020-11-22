# File Transfer Using TCP Socket in C | Socket Programming

**OS:** Ubuntu 20.04 LTS</br>
**IDE:** Visual Studio Code</br>

## Commands to be followed
### Server:
Compile Server and execute: 
```shell
gcc -o server server.c
./server
```
### Client:
Compile Client and execute: 
```shell
gcc -o client client.c
./client
```

Output on **Client side** console/terminal:
```shell
[+]Server socket created. 
[+]Connected to server.
[+] File data send successfully. 
[+]Disconnected from the server. 
```

Output on **Server side** console/terminal:
```shell
[+]Server socket created. 
[+]Binding Successfull.
[+]Listening...
[+]Data written in the text file
```

**Note:** </br>
**1.** You can see the changes in the **file.txt** and **file2.txt** which are present in the repo, since that data get transferred from one file to another !!</br>
**2.** The Libraries **#include<apra/inet.h>** are available only for the Linux Distros not for the windows, for windows we need to use **#include<winsock2.h>**</br>
**3.** Kindly Raise Issues if there is any problem or you can mail me at **psp316r@gmail.com** !!
