# CSE ieng6 Access Tutorial

## Step 1: Installing VSCode

Visit [The VSCode Website](https://code.visualstudio.com/) and download the build appropriate for your computer. Follow the installation instructions, and once you are finished you should see something that looks like this:

![Image](https://kabirvats.github.io/cse15l-report-1/vscode.PNG)

If you are on Windows, now is a good time to install git for Windows. 

## Step 2: Remotely Connecting

In VSCode, click Terminal, then new Terminal to start a new session in Terminal. Enter the following command, replacing the 'zz' with your three letter username for CSE15L.

'$ ssh cs15lwi23zz@ieng6.ucsd.edu'

Type yes if a verification prompt shows up, then enter your password. Afterwards, you should see something like this:

![Image](https://kabirvats.github.io/cse15l-report-1/terminal.PNG)

## Step 3: Trying Some Commands

Try out some commands! 'pwd', 'cd ..', 'ls', and 'cd' + file name in directory are all interesting ones. 

`pwd` - pwd stands for "present working directory" and prints the working directory the user is currently in.

`cd ..` - cd stands for "change directory," and the .. means to go to the parent directory of the directory the user is executing commands in.

`ls` lists the files within the work tree.

`cd [file name]` moves you into a file.

Starting in my student folder, I got a list of all of the protected student folders by using 'cd ..' followed by 'ls'.

![Image](https://kabirvats.github.io/cse15l-report-1/command.PNG)

Have fun!
