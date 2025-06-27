# feems-for-km

## Overview

feems-for-km is a package designed to demonstrate the modeling process of FEEMS and how to run simulations with a basic case.

## Prerequisites

- Python 3.10 or higher
- It is recommended to use a virtual environment to avoid conflicts with other packages.
- It is also recommended to use Microsoft Visual Studio Code as the IDE for development.

If you are using Microsoft Visual Studio Code, you can install the Python extension and Jupyter Notebook extension for better support and features. You can find the extension in the Extensions Marketplace by searching for "Python" or by visiting [Python Extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python).

## Installation

1. **Create the virtual environment:**

```bash
python -virtualenv .venv
```

This command will create a virtual environment named `.venv` in the current directory. If you are using a different name for your virtual environment, please adjust the command accordingly.
Make sure you have `virtualenv` installed. If you don't have it installed, you can install it using pip:

```bash
pip install virtualenv
```

If you are using Microsoft Visual Studio Code, you can also create a virtual environment using the command palette:

```
Ctrl + Shift + P (or Cmd + Shift + P on Mac) and type "Python: Create Environment" and select the option to create a virtual environment.
```

2. **Activate the virtual environment:**
   For Windows environment

```bash
.\.venv\Scripts\activate
```

For Linux or MacOS environment

```bash
source .venv/bin/activate
```

If you are using Microsoft Visual Studio Code, the virtual environment should be automatically activated when you open the terminal in the IDE. Otherwise, you can select the interpreter for the virtual environment by pressing `Ctrl + Shift + P` (or `Cmd + Shift + P` on Mac) and typing "Python: Select Interpreter" and selecting the interpreter for the virtual environment you just created.

3. **Install the dependencies:**

```bash
pip install -r requirements.txt
```

This command will install all the required dependencies for the project. If you are using Microsoft Visual Studio Code, you may have already installed the dependencies when you created the virtual environment. If you haven't, just run the command above in the terminal.

4. **Open the Jupyter Notebook and run the code:**

You can open the Jupyter Notebook in Microsoft Visual Studio Code. Otherwise, you can run the following command in the terminal:

```bash
jupyter notebook
```

This will open the Jupyter Notebook in your default web browser. You can then navigate to the notebook file and run the code cells to see how the FEEMS modeling process works.
