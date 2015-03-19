# Markov Decision Processes and Dynamic Optimization

Course module for Decision Analysis Tools course, March 2015 at the National Conservation Training Center

A static HTML version of this tutorial can be viewed [here](http://bit.ly/nctc_mdp). To run the tutorial yourself on your own machine, follow the installation instructions below.

## Installing Python and Required Packages

### Step 1: Install Python (Anaconda)

The easiest way to install the Python packages required for this tutorial is via [Anaconda](https://store.continuum.io/cshop/anaconda/), a scientific Python distribution offered by Continuum analytics. [Download Anaconda](http://continuum.io/downloads "Download Anaconda Python Distribution"), and run the installer.

### Step 2: Update packages

Once Anaconda is installed, there are a few steps required to install the packages that the tutorial uses. From your command line terminal, enter the following commands:

    conda update ipython ipython-notebook pandas pip
    pip install pymdptoolbox filterpy

### Step 3: Acquire course materials
    
When these have been installed, the next step is to download the tutorial materials. For those of you familiar with Git, you can simply clone the [GitHub repository](https://github.com/fonnesbeck/NCTC_course) to your machine. If you are unfamiliar with Git, you may download a [zip archive](https://github.com/fonnesbeck/NCTC_course/archive/master.zip) to your machine instead, and extract the files therein to a location of your choice.

### Step 4: Run IPython Notebook

The tutorial is contained in an IPython Notebook, an interactive interface for running code alongside the notes for the tutorial. IPython Notebooks are identified by a `.ipynb` extension on the file. There are two ways of starting up the notebook:

1. **From the command line**: In your command line terminal, move into the folder that you extracted the tutorial files to, and run:

        ipython notebook
        
    This should open your default browser, and show a list of files within the IPython Notebook interface. Then you should be able to double-click on the `Markov Decision Processes and Dynamic Optimization.ipynb` file to open the tutorial.
    
2. **Using the Anaconda launcher**: Anaconda may have created an icon labelled "Launcher" on your desktop, or in your Applications folder. Double clicking on this should bring up an interface with several options:

    ![Anaconda launcher](http://fonnesbeck-dropshare.s3.amazonaws.com/Screen-Shot-2015-03-18-12-17-58.png)

    Select the IPython Notebook, which should open your default browser, and show a list of files within the IPython Notebook interface. Then you should be able to double-click on the `Markov Decision Processes and Dynamic Optimization.ipynb` file to open the tutorial.
    
![IPython Notebook](http://fonnesbeck-dropshare.s3.amazonaws.com/Screen-Shot-2015-03-18-12-22-34.png)
