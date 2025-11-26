# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 12.08.2025
###  Reg No:212223240182
###  Name: VINOTH M P
# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv("/content/train.csv")
df = df.sort_values(by='ram')
plt.plot(df['ram'], df['price_range'], marker='o')
plt.title("Mobile Price Range vs RAM")
plt.xlabel("RAM (MB)")
plt.ylabel("Price Range")
plt.show()
```
# OUTPUT:

<img width="584" height="456" alt="image" src="https://github.com/user-attachments/assets/7d19c3f9-1d71-4590-b79e-5e1fa717ee8b" />



# RESULT:
Thus we have created the python code for plotting the time series of given data.
