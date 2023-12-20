# Read-from-CSV

## AIM:
To Write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv
### Step 3:
use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
print the output

## PROGRAM:
```
Developed by: TAMILARASAN K S.
Register Number:23000080
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Lokhnath10/Read-from-CSV/assets/138969918/db1def46-34bc-482c-8d1e-7fc828782461)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
