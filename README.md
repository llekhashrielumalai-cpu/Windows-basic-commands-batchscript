# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="606" height="223" alt="image" src="https://github.com/user-attachments/assets/cf67b114-e143-4e65-9a04-884964e76d9e" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="842" height="371" alt="image" src="https://github.com/user-attachments/assets/eb74ac6b-4bd8-46e1-9936-be8cb3df1cb6" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="828" height="352" alt="image" src="https://github.com/user-attachments/assets/80a78279-5e10-4652-bbf7-3257b26c7496" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="960" height="121" alt="image" src="https://github.com/user-attachments/assets/1cb46fdf-4e8d-4724-9b87-9d173d9e4b9e" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="892" height="143" alt="image" src="https://github.com/user-attachments/assets/273b6557-7744-4dbc-994f-e65befef1840" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="782" height="221" alt="image" src="https://github.com/user-attachments/assets/5a6620a7-7026-444b-8800-8c2ab32c580d" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="757" height="1059" alt="image" src="https://github.com/user-attachments/assets/1e2a6764-e97a-427b-ad7c-0f3cdc0e07c7" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="863" height="1106" alt="image" src="https://github.com/user-attachments/assets/3aea6eb4-55de-44a2-ba01-9d5d0c7617ce" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="826" height="188" alt="image" src="https://github.com/user-attachments/assets/a4c276c5-c021-4be5-a3b1-9c81aeff09d5" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="697" height="89" alt="image" src="https://github.com/user-attachments/assets/1deedafe-1c1f-44a2-885e-2cba7e99d51d" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="693" height="260" alt="image" src="https://github.com/user-attachments/assets/4ca7ff9f-2fff-4b13-84dd-3dd0b4320c09" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="715" height="209" alt="image" src="https://github.com/user-attachments/assets/f1aff06a-bb5f-4555-a3fa-b3d548f09330" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="696" height="111" alt="image" src="https://github.com/user-attachments/assets/4d7d5ff1-e394-4051-b6c8-63701bcd9338" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="753" height="442" alt="image" src="https://github.com/user-attachments/assets/90364bf5-329a-40a4-a7c1-bad3ca60bf7a" />



# RESULT:
The commands/batch files are executed successfully.
