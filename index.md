# How to login to a course-specific account on ieng6

**Step 1: Reset your password**

Go to [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php) and login with your Active Directory id. Note down what the three letters at the end of your course access code are. Click change your password and follow the instructions.
Make sure to click the button to not change all of your passwords if you want to keep your same password for other UCSD applications.

**Step 2: Download VSCode**
Go to [code.visualstudio.com/code.visualstudio.com](code.visualstudio.com/code.visualstudio.com/) to download the IDE. Click the download button in the
top right. Next click a download button based on the OS that you are running. Once the installer is downloaded, open it and follow the instructions.
It should look like this after:
![Image](Screen%20Shot%202023-01-12%20at%204.44.27%20PM.png)

**Step 3: Connecting to the server**

Create a new terminal in VSCode by clicking "Terminal" in the task bar and clicking "New Terminal". Next type in `ssh cs15lwi23XX@ieng6.ucsd.edu` where XX represents the three letters at the end of the access code from
the website from step 1. Then a prompt should come up where you can answer yes. It will then prompt you to ask for your password. Type in the new password that you set and then the terminal window should look something like this:
![Image](Screen%20Shot%202023-01-26%20at%201.50.16%20PM.png)

**Step 4: Try out commands on the terminal**

Try commands such as:
* `ls`: see what files/folders are on the path
* `cd`: follow this command with the file name to view the file
* `cd ..`: to try going back to the parent directory

Press exit to disconnect from the server when you are done.
![Image](Screen%20Shot%202023-01-26%20at%202.00.53%20PM.png)
