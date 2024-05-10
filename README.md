# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
# NAME:PRASANNA I
# REGNO:212223220079

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
```
mkdir %userprofile%\Desktop\MyLab
```
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/6a63c3db-b025-4bac-a9cd-3ebc36e8a87e)


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/d87c334e-f6ec-43cb-81c4-60598da13e1f)



## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab
```
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/3ce203e4-d4ed-4017-8b41-f694945ae1ac)
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/dac1c88a-5729-445d-89cd-1327e932cb30)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/27e79fec-b443-4ed8-b00f-de45cb430a36)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup
```
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/7d1c687a-68a3-4820-8af3-77d288edf4aa)
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/0a66ac4b-0ea1-468a-a7dd-dd43d940dfcd)


## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/ec55c4cc-6d46-4ad5-89db-70510bd00f62)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```






## OUTPUT
![image](https://github.com/prasanna2006I/Windows-basic-commands-batchscript/assets/150161282/c87fd264-4312-451b-ab93-f4ce9e81b382)





# RESULT:
The commands/batch files are executed successfully.

