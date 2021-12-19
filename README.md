# Machine Learning Assessment - Scikit-Learn and Scipy-Stats



Machine Learning and Statistics - Assessment 2021 GMIT

This repository contains Jupyter notebooks and other relevant files demonstrating my work on the Python packages  **Scikit-Learn** and **Scipy-Stats**

***

<br>

## Install

1. Download [Anaconda](https://www.anaconda.com/products/individual).
2. Download [cmder](https://cmder.net/) if on Windows.
3. Download the notebooks to your computer

<br>

## Run

Here's how to run the notebooks on this project:

1. Open cmder (or any other terminal)
2. run `jupyter notebook`
3. Go to browser

<br>

## Explore

Have a look at the two notebooks in this repository in Jupyter.

Some interesting aspects:

-The notebook `scipy-stats.ipynb` has an interesting example of **Image Processing**. You can edit the parameters of the plots to see different effects (`ndimage.rotate(panda, value)`):
```python
from scipy import ndimage, misc
from matplotlib import pyplot as plt
panda = misc.face()
#rotatation function of scipy for image – image rotated 135 degree
panda_rotate = ndimage.rotate(panda, 135)
plt.imshow(panda_rotate)
plt.show()
```


***
<br>

## Quick viewing steps

The notebooks can also be viewed at the following image links:


**Scikit-Learn:**

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/thenriq/machine_Learning_Assessment/blob/main/Scikit-Learn.ipynb)

<br>

**Scipy-Stats**

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/thenriq/machine_Learning_Assessment/blob/main/scipy-stats.ipynb)

<br>

<br>

# Contact

[Email: g00387821@gmit.ie](mailto:g00387821@gmit.ie)

[Linkedin](https://www.linkedin.com/in/thiago-limait/)

