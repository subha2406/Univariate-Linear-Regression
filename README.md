# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
```
 ![eqn1](./eq1.jpg)
4.	Compute the y -intercept of the line by using the formula:
![eqn2](./eq2.jpg)  
5.	Use the slope m and the y -intercept to form the equation of the line.
6.	Obtain the straight line equation Y=mX+b and plot the scatterplot.
## Program
```
import numpy as np
import matplotlib.pyplot as plt
X=np.array(eval(input()))
Y=np.array(eval(input()))
X=mean=np.mean(X)
Ymean=np.mean(Y)
num.den=0,0
for i in range(len(X)):
    num += (x[i]-Xmean)*(Y[i]-Ymean)
    den += (X[i]-Xmean)**2
m=num/den
c=Ymean-m*Xmean
print(m,c)
Y_pred=m*X+c
print (Y_pred)
plt.scatter(X,Y)





```
## Output
![WhatsApp Image 2024-05-24 at 18 39 50_6a936d2c](https://github.com/subha2406/Univariate-Linear-Regression/assets/155226504/bf668a57-b9e7-4987-9fc7-64bfe3c359b8)
![WhatsApp Image 2024-05-24 at 18 40 05_3f6476a1](https://github.com/subha2406/Univariate-Linear-Regression/assets/155226504/872ab18e-8e8e-467c-9908-7a181bddd21d)


## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
