# Python Scripts for DER Voltage Regulation Analysiss 

This repository contains code and examples to illustrate various aspects of the volt-var functionality in IEEE Standard 1547-2018.  

## Directory of Python Scripts and Notebooks

- **vqpoints.ipynb**; Jupyter Notebook that illustrates volt-var characteristics
    - invoke with **jupyter notebook vreg.ipynb** from a command prompt
    - or use **vqpoints.bat** launcher script for Windows
    - or use **vqpoints.sh** launcher script for Mac OS/Linux
    - **vqpoints.pdf** contains the default output tables and plots
- **vreg.ipynb**; Jupyter Notebook that illustrates volt-var performance
    - invoke with **jupyter notebook vreg.ipynb** from a command prompt
    - or use **vreg.bat** launcher script for Windows
    - or use **vreg.sh** launcher script for Mac OS/Linux
    - **vreg.pdf** contains the default outputs

## Python and Jupyter Notebook Support

To prepare your computer for running these examples:

1. Install Python 3 if necessary. This is available from [Python Site](https://python.org), 
   [Anaconda/Miniconda](https://www.anaconda.com/), or the 
   [Microsoft Store](https://apps.microsoft.com/store/detail/python-310/9PJPW5LDXLZ5).
   - On the second panel of Python 3's installer, **select the option** that adds Python variables to your system environment, which includes the **path**.
2. Install the Python support packages as necessary:
   - Open a **Command Prompt** from the Start / Windows System menu.
   - Enter **pip install matplotlib scipy** for plotting and numerical support, see [Matplotlib](https://matplotlib.org/), [numpy](https://numpy.org/doc/stable/user/index.html), and [scipy](https://scipy.org/).
   - Enter **pip install jupyter ipympl ipywidgets** for a browser-based interface to Python, see [Jupyter Notebook](https://jupyter.org).

Copyright 2023, Meltran, Inc

