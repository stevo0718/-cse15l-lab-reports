# LAB REPORT 3

*There are 3 parts in this lab report*

1. Streamlining ssh Configuration
2. Setup Github Access from ieng6
3. Copy whole directories with `scp -r`

# 1. Strealining ssh Configuration

***

This is where my config file is located.

![configLocation](configLocation.png)

And this is how I edited the config file.

![configFile](configFile.png)

After setting up this file, I am able to log in to my account with shorter types 
such as: `ssh ieng6` like the following image:

![ssh](ssh.jpg)

And I could also move files to my account with shorter types like the following image.

![scp](scp.jpg)

# 2. Setup Github Access from ieng6

***

# 3. Copy whole directories with `scp -r`

***

With the command:

```
scp -r *.java *.md lib/ cs15lsp22@ieng6.ucsd.edu:markdown-parse
```
I am able to copy the whole directory of markdown-parse to the server with just one commmand.

An example of using this command is the following image:

![scpAll](scpAll.png)

After adding the file, I am able to compile and run the tests on the server.

![RunOnServer](RunOnServer.png)

Please ignore the failed test. I am still working on the edge cases.

And for even more convenient purpose, I can move the files and run commands together in one line 
using `:` to combine the commands.

![Together](Together.jpg)