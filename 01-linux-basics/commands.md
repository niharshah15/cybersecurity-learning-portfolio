---------- Commands and their description ----------

-> "echo"
Description: Output any text that we provide.
Eg: echo Hello
Output: Hello

-> "whoami"
Description: It is used to find out the username we are logged in as.
Eg: whoami   
Output: Abcd

-> "ls" - list
Description: Used to list all the files and directories are there in it.
Eg: ls  
Output: file1.txt folder1 folder2

-> "cd" - change directory
Description: Used to change the directory.
Eg: cd folder1  
    ls
Output: picture1.jp picture2.jpeg

-> "cat"
Description: Used to output the contents of file.
Eg: cat todo.txt  
Output: Here are the tasks for me to do later.

-> "pwd" - print working directory
Description: Used to provide the full path to our current working directory.
Eg: pwd
Output: /home/ubuntu

-> "find"
Description: Used to find the path of file where it is present.
Eg: find -name passwords.txt
Output: ./folder1/passwords.txt

-> "grep"
Description: Used to search entire contents of file for the entries we are searching for.
Eg: grep "81.143.211.90" access.log
Output: 81.143.211.90 - - [25/Mar/2021:11:17 + 0000] "GET / HTTP/1.1" 200 417 "-" "Mozilla/5.0 (Linux; Android 7.0; Moto G(4))"

---------- Operators ----------

-> Operator "&"
Description: Used to execute command in background and allows us to do other things.

-> Operator "&&"
Description: By using this the command on the right side will only be executed if the command on left side executes successfully.
Eg: command1 && command2

-> Operator ">"
Description: Used to redirect the output of file.
Eg: echo "This is the first line." > file.txt

-> Operator ">>"
Description: Used to redirect the output of file, adding new data to the end of existing content of file.
Eg: echo "This line is appended." >> logfile.txt
