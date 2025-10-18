# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 Include the necessary coding and corresponding screenshots

import matplotlib.pyplot as plt

x_values = [ 0, 1, 2, 3, 4, 5 ]
y_values = [ 0, 1, 4, 9, 16, 25]

plt.plot(x_values, y_values)

plt.show()

<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/32855880-9d60-4f0c-bb1d-761ea82222a3" />

import matplotlib.pyplot as plt

x = [1, 2, 3]
y = [2, 4, 1]

plt.plot(x, y)

plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My first graph!')

plt.show()

<img width="771" height="563" alt="image" src="https://github.com/user-attachments/assets/64cd2c22-b034-4fc8-887d-661ee88ea5ae" />

import matplotlib.pyplot as plt

# line 1 points
x1 = [1, 2, 3]

y1 = [2, 4, 1]

plt.plot(x1, y1, label="line 1")

x2 = [1, 2, 3]

y2 = [4, 1, 3]

plt.plot(x2, y2, label = "line 2")

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('Two lines on same graph!')

plt.legend()

plt.show()

<img width="771" height="563" alt="image" src="https://github.com/user-attachments/assets/c8a3bd42-883c-4df5-a56e-24293d4a8ea4" />

import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5, 6]

y = [2, 4, 1, 5, 2, 6]

plt.plot(x, y, color='green', linestyle='dashed', linewidth = 3,
         marker='o', markerfacecolor='blue', markersize=12)

plt.ylim(1, 8)

plt.xlim(1, 8)

plt.xlabel('x - axis')

plt.ylabel('y - axis')


plt.title('Some cool customizations!!')

plt.show()

<img width="758" height="563" alt="image" src="https://github.com/user-attachments/assets/98c7335d-b9f9-4875-b517-631b262ad992" />


yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]

plt.plot(yield_apples)

<img width="769" height="505" alt="image" src="https://github.com/user-attachments/assets/b4c945d6-5b24-4f05-b652-e801d7d248e2" />


years = range(2000, 2012)

apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]

oranges = [0.962, 0.941, 0.930, 0.923, 0.918, 0.908, 0.907, 0.904, 0.901, 0.898, 0.9, 0.896,0.8]

plt.plot(years, apples)

plt.plot(years, oranges)

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)')

<img width="769" height="505" alt="image" src="https://github.com/user-attachments/assets/01aeefd5-54bd-4467-bd04-42492ddbf561" />



import matplotlib.pyplot as plt 

years = range(2000, 2012)

apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]

oranges = [0.962, 0.941, 0.93, 0.923, 0.918, 0.908, 0.907, 0.904, 0.901, 0.898, 0.9, 0.896]

plt.plot(years, apples)

plt.plot(years, oranges)

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)')

plt.title('Crop Yields in Kanto')

plt.legend(['Apples', 'Oranges'])

plt.show()


<img width="451" height="299" alt="image" src="https://github.com/user-attachments/assets/9a6829a2-2c29-44d1-87e2-06dd9a739bb9" />

import matplotlib.pyplot as plt

x_values = [0,1,2,3,4,5]

y_values = [0,1,4,9,16,25]

plt.scatter(x_values, y_values, s=30, color="blue")

plt.show()

<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/c064a56d-fcd5-4f18-9d66-3739ba5b9b29" />


import matplotlib.pyplot as plt

x = [1,2,3,4,5,6,7,8,9,10]

y = [2,4,5,7,6,8,9,11,12,12]

plt.scatter(x, y, label="stars", color="green", marker="*", s=30)

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('My scatter plot!')

plt.legend()

plt.show()


<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/bf56a9c6-0fe8-4f07-99c5-313db8483eb4" />



import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

x = np.arange(0,10)
y = np.arange(11,21)

# The following lines are for display and are not executable code:
# x
# array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])

plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/f4e63483-bf98-4ac5-b435-0ae0f3002fa2" />


y = x*x 

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2, markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')

<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/c223f050-09ab-4801-ad5a-deb44d73138f" />



plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')

<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/ce1b673a-2261-419c-aa8a-836eeb5498aa" />

x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)
plt.title("sine wave form")

plt.plot(x, y)
plt.show()

<img width="773" height="536" alt="image" src="https://github.com/user-attachments/assets/236b6800-909c-4493-930a-92100ebef2bc" />


import matplotlib.pyplot as plt

import numpy as np

x = [1, 2, 3, 4, 5]

y1 = [10, 12, 14, 16, 18]

y2 = [5, 7, 9, 11, 13]

y3 = [2, 4, 6, 8, 10]

plt.fill_between(x, y1, color='blue')

plt.fill_between(x, y2, color='green')

plt.plot(x, y1, color='red')

plt.plot(x, y2, color='black')

plt.legend(['y1','y2'])

plt.show()

<img width="756" height="505" alt="image" src="https://github.com/user-attachments/assets/95e03dcb-5c38-4f6f-9218-31fc2a54c0c3" />

plt.stackplot(x, y1, y2, y3, labels=['Line 1', 'Line 2', 'Line 3'])

plt.legend(loc='upper left')

plt.title('Stacked Line Chart')

plt.xlabel('X-axis')

plt.ylabel('Y-axis')

plt.show()

<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/3badb0c8-dd28-441f-aa45-11e5ee303242" />


import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline

x = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
y = np.array([2, 4, 5, 7,8, 8, 9, 10, 11, 12])

spl = make_interp_spline(x, y)

x_smooth = np.linspace(x.min(), x.max(), 100)

y_smooth = spl(x_smooth)

plt.plot(x, y, 'o', label='data')
plt.plot(x_smooth, y_smooth, '-', label='spline')
plt.legend()
plt.show()

<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/98186e26-8dbf-4296-acf0-6b34c599603c" />



import matplotlib.pyplot as plt
values = [5, 6, 3, 7, 2]
names = ["A", "B", "C", "D", "E"]

plt.bar(names, values, color="green")
plt.show()

<img width="725" height="505" alt="image" src="https://github.com/user-attachments/assets/264d9216-516e-4a98-8534-71f7ac7596b6" />

import matplotlib.pyplot as plt
values = [5, 6, 3, 7, 2]
names = ["A", "B", "C", "D", "E"]

plt.barh(names, values, color="yellowgreen")
plt.show()

<img width="727" height="505" alt="image" src="https://github.com/user-attachments/assets/4465ac66-d684-4d6d-99ee-e7b9ef0e1c98" />


import matplotlib.pyplot as plt

height = [10, 24, 36, 40, 5]

names = ['one', 'two', 'three', 'four', 'five']

c1 = ['red', 'green']
c2 = ['b', 'g'] # we can use this for color
plt.bar(names, height, width=0.8, color=c1)

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('My bar chart!')

plt.show()

<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/ee87be01-a455-473b-ba90-cad346d565d7" />


x = [2,8,10]
y = [11,16,9]
x2 = [3,9,11]
y2 = [6,15,7]
plt.bar(x, y, color='r')
plt.bar(x2, y2, color = 'g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()

<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/0dddfbac-8f59-4639-9479-617eaa3c58d7" />


import matplotlib.pyplot as plt

ages = [2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]

range = (0, 100)
bins = 10

plt.hist(ages, bins, range, color='green', histtype='bar', rwidth=0.8)

plt.xlabel('age')

plt.ylabel('No. of people')

plt.title('My histogram')

plt.show()

<img width="752" height="563" alt="image" src="https://github.com/user-attachments/assets/8ac4cf5f-6a26-42af-9a80-661fdb85fa76" />

import matplotlib.pyplot as plt

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]

plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()

<img width="725" height="505" alt="image" src="https://github.com/user-attachments/assets/9a50a9a7-ae62-47df-b5b5-172cfa135d81" />

import matplotlib.pyplot as plt
import numpy as np


np.random.seed(0)
data = np.random.normal(loc=0, scale=1, size=100)


fig, ax = plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')

plt.show()

<img width="768" height="563" alt="image" src="https://github.com/user-attachments/assets/5248906c-1835-452a-acc9-1db0af8ddd68" />


import matplotlib.pyplot as plt

activities = ['eat', 'sleep', 'work', 'play']

slices = [3, 7, 8, 6]

colors = ['r', 'y', 'g', 'b']

plt.pie(slices, labels = activities, colors=colors,
        startangle=90, shadow = True, explode = (0, 0, 0.1, 0),
        radius = 1.2, autopct = '%1.1f%%')


plt.legend()
plt.show()

<img width="536" height="490" alt="image" src="https://github.com/user-attachments/assets/23133c64-a28b-459c-b37a-da53f6a43f08" />


labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [215, 130, 245, 210]
colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode = (0, 0.4, 0, 0.5)

plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=True)

plt.axis('equal')
plt.show()


<img width="698" height="472" alt="image" src="https://github.com/user-attachments/assets/9fb96bc2-2665-45f1-9d8d-a8ef664784e7" />


# Result:
 Thus, the program to Perform Data Visualization using matplot python library for the given data was 
implemented.
