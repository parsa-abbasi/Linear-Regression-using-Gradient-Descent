# Linear Regression using Gradient Descent
Demonstrating how solve a linear regression problem using gradient descent.

You can read detailed description about gradient descent on `.ipynb` file.

## Execution
This example implemented as python 3 notebook in google colab.
You can simply upload `GradientDescent.ipynb` file to your google colab drive.

## Input
You can upload the dataset file (`data.csv`) to google colab using this code :
```
from google.colab import files
uploaded = files.upload()
```
We parse our dataset into an array using :
```
points = genfromtxt('data.csv', delimiter=',')
```

## Output
The output will look like this

![Output Plot](https://raw.githubusercontent.com/parsa-abbasi/Linear-Regression-using-Gradient-Descent/master/GradiantDescentPlot.png)
```
After 5000 iterations b = 0.3239436244645088, m = 1.4731250921538916, error = 112.47667596020761
```

## Resources
*   [Intro - The Math of Intelligence by Siraj Raval](https://youtu.be/xRJCOz3AfYY)
*   [An Introduction to Gradient Descent and Linear Regression by Matt Nedrich](https://spin.atomicobject.com/2014/06/24/gradient-descent-linear-regression/)
*   [How to Do Linear Regression using Gradient Descent by Siraj Raval](https://youtu.be/XdM6ER7zTLk)
*   [Linear Regression Tutorial Using Gradient Descent for Machine Learning by Jason Brownlee](https://machinelearningmastery.com/linear-regression-tutorial-using-gradient-descent-for-machine-learning/)
*   [Linear Regression with Gradient Descent - Intelligence and Learning by Daniel Shiffman](https://youtu.be/L-Lsfu4ab74)
