# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
 Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.
## PROGRAM:
```
#Developed By:Giftson rajarathianam N
#Register No: 212222233002
with open('f11.txt','r') as f1:
    with open ('f12.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:

![image](https://github.com/gifty003/copy-file/assets/145822352/06b446ca-1456-488e-a8ef-85668e8e071a)
![image](https://github.com/gifty003/copy-file/assets/145822352/b38d149f-703e-4959-a74c-68eaddb38ed5)
![image](https://github.com/gifty003/copy-file/assets/145822352/aaf8712b-e92e-40f9-a201-9efd882734ba)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
