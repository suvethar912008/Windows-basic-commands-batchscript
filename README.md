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

<img width="750" height="147" alt="Screenshot 2026-09-07 223104" src="https://github.com/user-attachments/assets/cd792580-35e6-4eb7-9b74-952a6d8e0b22" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="803" height="107" alt="image" src="https://github.com/user-attachments/assets/cb956b42-e7f1-49c8-a51f-be8acaff2ca8" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="803" height="107" alt="image" src="https://github.com/user-attachments/assets/cb956b42-e7f1-49c8-a51f-be8acaff2ca8" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="742" height="112" alt="Screenshot 2026-09-07 223420" src="https://github.com/user-attachments/assets/1b2c5f12-9899-4724-9b20-466d9a6cfacb" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="742" height="112" alt="Screenshot 2026-09-07 223420" src="https://github.com/user-attachments/assets/1b2c5f12-9899-4724-9b20-466d9a6cfacb" />

Remove the file hello1.txt

## COMMAND AND OUTPUT


<img width="807" height="43" alt="Screenshot 2026-09-07 223529" src="https://github.com/user-attachments/assets/14ccf06d-6424-4618-84ca-67449cf58556" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT


<img width="787" height="167" alt="image" src="https://github.com/user-attachments/assets/c532f0d5-74fe-4106-84f8-666d44f87896" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="787" height="167" alt="image" src="https://github.com/user-attachments/assets/c532f0d5-74fe-4106-84f8-666d44f87896" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="780" height="205" alt="image" src="https://github.com/user-attachments/assets/8dd6f1df-6e4a-4e7e-a439-732238287ede" />



## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="677" height="101" alt="image" src="https://github.com/user-attachments/assets/0070a984-9dcc-4e55-a00c-30b3c6732132" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="677" height="101" alt="image" src="https://github.com/user-attachments/assets/0070a984-9dcc-4e55-a00c-30b3c6732132" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="677" height="101" alt="image" src="https://github.com/user-attachments/assets/0070a984-9dcc-4e55-a00c-30b3c6732132" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="677" height="101" alt="image" src="https://github.com/user-attachments/assets/0070a984-9dcc-4e55-a00c-30b3c6732132" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="677" height="101" alt="image" src="https://github.com/user-attachments/assets/0070a984-9dcc-4e55-a00c-30b3c6732132" />


# RESULT:
The commands/batch files are executed successfully.

