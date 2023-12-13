# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:
Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

Step 2:
Read the file and store in a variable.

Step 3:
Now create a new file in which we want to paste the content using write access mode.

Step 4:
Use write function to copy the read file that has been stored in the variable.

Step 5:
The content in the original file will be copied in the new file.

Step 6:
End the program.

## PROGRAM:
```
#Devolped By:Masina Sree Karsh
#Ref no: 23005860
with open('sample.txt','r') as file1:
 with open ('san1.txt','a') as file2:
 for line in file1:
 file2.write(line)
```
## OUTPUT:

![image](https://github.com/sreekarsh/copy-file/assets/139841918/037fdb8d-c9e1-41a5-aa59-c5ceaffb2655)


![image](https://github.com/sreekarsh/copy-file/assets/139841918/fbc6c440-3d37-4523-8489-f9505b9e7199)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
