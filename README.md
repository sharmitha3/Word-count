# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
Read the text using read() function. 
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```
Developed by : SHARMITHA V
Registered number: 212223110048

def wordcount(filename):
    count=0
    with open(filename,"r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```
### OUTPUT:
![image](https://github.com/sharmitha3/Word-count/assets/145974496/0ec67a4f-afb0-4e91-bf94-0084e539eb0b)

![image](https://github.com/sharmitha3/Word-count/assets/145974496/c79ec173-048f-4596-afd2-8f979e95b36d)


## RESULT:
Thus the program is written to find the word count from a text.
