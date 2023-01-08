# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1:
Get the value from the user
### Step 2: 
Assign the values
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
print the result
### Step 5: 
End the program
### PROGRAM:
~~~
   python
   #Program to find the distance between two points.
#Developed by: panimalar.p
#RegisterNumber:22009107
import math 

def distance(point1,point2):
    x1, y1 = point1
    x2, y2 = point2
    return math.sqrt((x2-x1)**2 + (y2-y1)**2)
point1 = (4, 2)
point2 = (10,6)
    
distance = distance(point1,point2)
print(f"{distance:.2f}")
~~~  


### OUTPUT:
![](./distance.png)


### RESULT:
Thus distance of two points created successfully
