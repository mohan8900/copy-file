# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

step 1:
start the program

Step 2:
open file1.txt in read mode

Step 3:
assign para to fp.read() of file1.txt

Step 4:
again open a new file file2.txt in write mode

Step 5:
use write function to copy the file contents

Step 6:
end the program

## PROGRAM:
```
NAME:A.K MOHAN RAJ
REF NO:21001890

with open("record.txt","r")as fp:
    with open("file1.txt","w")as fp1:
        line=fp.read()
        fp1.write(line)
```

### OUTPUT:
![git log](s1.png)
![git log](s2.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.