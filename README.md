# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Create a file and add some content into it.

### Step 2: 

 Open file using with keyword/built-in function in read mode.

### Step 3: 
Use read() to read the contents of the file.

### Step 4:  
Split the lines using split().

### Step 5: 
Iterate the list and increment the count

### Step 6: 
Print the output.

## PROGRAM:
```python
#program to find the number of words
#developed by:vinushcv
#register number:22001897
with open("ok.txt","r") as f:
    a=0
    for i in f:
        b=i.split()
        a+=len(b)
    print("number of words :",a)
```
## OUTPUT:![output](outdone.png)
![output](outrun.png)


## RESULT:
Thus the program is written to find the word count from a text.
