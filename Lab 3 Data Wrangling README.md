# GEOG 464 - Lab 3

## Data Wrangling in Python

Like with the previous lab, you will need to open the Jupyter notebook file (*.ipynb*) contained in this assignment folder. You can do this either in VS Code or in [Google Colab](https://colab.research.google.com/).

If you are using your own local Python installation in VS Code, recall the following steps from previous labs in order to open the Jupyer notebook:

- Navigate to your working folder for this class, and create a new folder for 'Lab3'
- Create a new virtual environment for this lab, or use the same one as the previous lab [1]
    - e.g. `python -m venv venvLab3` (may be `python3` depending on your setup)
- Activate the virtual environment
    - e.g. `. venvLab3/bin/activate`(or `. venvLab3/Scripts/activate`)
- Install the necessary Python packages, which are listed in the provided *requirements.txt* file
    - e.g. `pip install -r requirements.txt` (may be `pip3` depending on your setup)
    - Note that these packages include Jupyter Lab and Pandas, as well as their dependancies
- Start a Jupyter Lab local server
    - e.g. `jupyter-lab`
    - Unless you add the `--no-browser` flag, the Jupyter notebook will automatically open in your browser; you can either complete the lab there (very similar to Colab), or work in VS Code by following the next step
- Open the Jupyer notebook file (*.ipynb*) in VS Code and connect to the server's kernel by pasting the generated URL (see terminal output) into the dialog box (ask if unclear)
    - The URL most likely begins with an address similar to 'localhost' or '127.0.0.1'

\[1\] Again, it is ultimately up to you how you want to manage your virtual environments. You could have one for each project/lab, or one for the entire class. You could likewise not use virtual environments at all, and install all these packages on your system Python installation. It is up to you to manage your own setup. However, I recommended using virtual environments.

**Instructions and tasks for this lab are in the *Lab-3.ipynb* file.**
