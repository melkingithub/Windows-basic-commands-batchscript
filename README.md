# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.

### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/d26e5b0f-8eca-4900-a53d-c8b351d3188d)
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/cd03ee59-c807-40a2-9af1-3049a3dbb8d9)
List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/9d4b9e53-075d-4c8e-a778-e05e1fe18eaf)
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/e83000e1-c307-45b1-b585-d385206af428)
Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/e9a83bbb-d971-412f-8d5d-d73aa781c741)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT
![image](https://github.com/user-attachments/assets/0a260b5f-c804-46cd-83c0-cea13cfaf465)





## RESULT:
The commands/batch files are executed successfully.

