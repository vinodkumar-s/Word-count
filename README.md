# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1: Open file in read mode.

### Step 2: Read the text using read funcion.
 
### Step 3: Split the text using space separator.

### Step 4: The length of the split list should be equal to the number of words in the text file.

### Step 5: Now give print().

### Step 6: End the program.

## PROGRAM:
## developed by : S.vinod kumar
## reference number: 22004903
``` python
num=0
with open("file1.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)

```
### OUTPUT:
![output](/output2.jpg)
![output](/output1.jpg)


## RESULT:
Thus the program is written to find the word count from a text.
