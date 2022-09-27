# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

## PROGRAM:
```
with open("git.txt","r") as f1:
    with open("MyFile.txt","a") as f2:
        for line in f1:
            f2.write(line)
 ```           


### OUTPUT:
![ouput](./t1.png)

MyFile.txt  =  
 ![ouput](./t02.png)

git.txt =

![ouput](./t2.png)

copied file = 

![ouput](./t3.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.