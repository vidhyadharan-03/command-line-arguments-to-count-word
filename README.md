# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Get the file name using command arguments

## Step 2:
Now read the content in the file

## Step 3:
use split(

## Step 4:
Now read the no.of words in file

## Step 5:
Print number of words present in given file

## Step 6:
End of the program

## PROGRAM:
Developed by : R.vidhyadharan

Register no : 22008663
~~~py
import sys
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
~~~


### OUTPUT:
![out](/output.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
