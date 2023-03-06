# Dylan_Challenge_002

Your challenge habibi is to create a simple environment where I could do some data science work.

The trick will be you need to assume that I have no libraries or local environment on my computer.

Let's work with conda and pip to create a file, requirements.txt, that will allow me to install all the libraries I need to do my work.

## Mohammed's Commands Here:

```

#### Create requirements file => to create requirements file, you need to create an environment called "challenge". To do so, run the following commands in your terminal by order (do not copy "$")
$cd .\Dylan_Challenge_002
$conda env export --file requirements.yml
$conda env create -n challenge -f requirements.yml
$conda activate challenge

#### Install libraries for data science.
$pip install python NumPy Pandas Matplotlib Scikit-learn

Note: To ensure you have installed the libraries, run those commands in your terminal, you should not see an error message:
$python
>>> import pandas as pd
>>> import matplotlib
>>> import numpy
>>> import sklearn

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#### install libraries from a requirements file
$cd .\Dylan_Challenge_002
$conda env export --file requirements.yml
$conda env create -n challenge -f requirements.yml
$conda activate challenge

#### list  the currently installed libraries
$python
>>> import pandas as pd
>>> import matplotlib
>>> import numpy
>>> import sklearn
```
