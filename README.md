# Read-from-CSV

## AIM:
To write a program for reading the csv file content
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of row returned is defined in pandas option settings.
### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
#DEVELOPED BY: Laakshit D
#REGISTER NO: 22000680

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```
## OUTPUT:
![output](/Screenshot%20from%202023-01-26%2020-23-23.png)
## RESULT:
Thus the program executed successfully for read csv file.