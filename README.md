ht#  Mean and variance of a discrete  distribution


# Aim : 

To find mean and variance of arrival of objects from the feeder using probability distribution


# Software required :  

Python and Visual components tool

# Theory:

The expectation or the mean of a discrete random variable is a weighted average of all possible
values of the random variable. The weights are the probabilities associated with the corresponding values. 
It is calculated as,

![image](https://user-images.githubusercontent.com/103921593/192938463-e34177f4-f188-48a0-bda2-8f6d1d660ed2.png)

The variance of a random variable shows the variability or the scatterings of the random variables.
It shows the distance of a random variable from its mean. It is calcualted as

![image](https://user-images.githubusercontent.com/103921593/192938695-99fedc01-34d5-4d36-84df-5880e766ed0c.png)


# Procedure :






<img src="https://github.com/user-attachments/assets/de1d6c19-005b-491b-8a0d-531779e449d5" width="1000" height="10000000"/>


<img src="https://github.com/user-attachments/assets/de1d6c19-005b-491b-8a0d-531779e449d5" width="1000" height="10000000"/>

























      


# Experiment :

![image](https://user-images.githubusercontent.com/103921593/229993174-5b67e57e-3e01-4ac4-9f83-410a932b22bf.png)

# Program :
```
import numpy as np
n = int(input("Enter the value of n : "))
print("Value of n =", n)
import numpy as np
n = int(input("Enter the value of n : "))
print("Value of n =", n)
InputVal = {}
for i in range(1, n+1):
    val = int(input(f"Enter the value no {i} : "))
    try:
        InputVal[val] += 1
    except:
        InputVal[val] = 1
print(f"{i} Values Collected Successfully")
InputVal = {}
for i in range(1, n+1):
    val = int(input(f"Enter the value no {i} : "))
    try:
        InputVal[val] += 1
    except:
        InputVal[val] = 1
print(f"{i} Values Collected Successfully")
mean = 0
for key, val in InputVal.items():
    mean += key*(val/n)
print(f"Mean = {mean:.3f}")
mean = 0
for key, val in InputVal.items():
    mean += key*(val/n)
print(f"Mean = {mean:.3f}")
ex2 = 0
for key, val in InputVal.items():
    ex2 += ((key**2) * val/n)
var = ex2 - mean**2
print(f"Variance : {var:.3f}")
ex2 = 0
for key, val in InputVal.items():
    ex2 += ((key**2) * val/n)
var = ex2 - mean**2
print(f"Variance : {var:.3f}")
from math import sqrt
sdtDeviation = sqrt(var)
print(f"Standard Deviation = {sdtDeviation:.3f}")
from math import sqrt
sdtDeviation = sqrt(var)
print(f"Standard Deviation = {sdtDeviation:.3f}")
```


# Output : 

<img src="https://github.com/user-attachments/assets/de1d6c19-005b-491b-8a0d-531779e449d5" width="1000" height="10000000"/>

<img src="https://github.com/user-attachments/assets/de1d6c19-005b-491b-8a0d-531779e449d5" width="1000" height="10000000"/>























# Results :

<img src="https://github.com/user-attachments/assets/de1d6c19-005b-491b-8a0d-531779e449d5" width="1000" height="10000000"/>

