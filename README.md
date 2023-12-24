# command-line-arguments-to-count-word
## AIM:
To write a Python program for getting the word count from the contents of a file using command line arguments.
## EQUIPMENT REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific action of interest
### Step 2: 
On the same location as the text file, create a python program file.
## Step 3: 
In the python Program, import sys and open a text file with the argument "sys.argv[1]"
## Step 4:  
using read() and split(), split the lines in the file into a sequence of words

### Step 5: 
using len() count the number of words in the text file

### Step 6: 
In the command prompt, initiate Python followed by the program name and text file name to get the output
## PROGRAM:
```
#python program for getting the word count from the contents of a file using command line arguments.
#Develpoed By: SREEKUMAR S
#RegisterNumber: 23008070
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word=line.split()
        count+=len(word)
print("Word count in file =",count)
```

### OUTPUT:
![Screenshot 2023-12-24 205220](https://github.com/guru14789/command-line-arguments-to-count-word/assets/151705853/170085eb-2ced-4226-951d-c84b4171c4dc)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
