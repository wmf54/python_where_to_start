# How To Get Started With Python
## Introduction
I have been using Python for work for several years now, and I try to be a vocal proponent of its utility in science
and engineering. Becasue of this, I have been asked by several people, that are already trained scientists or engineers, 
how to get started with Python. The purpose of this is to document some frequently asked questions and answers I have 
given in these scenarios. Hopefully it helps others to get started who have little to no formal training in  
programming with Python.

## How do I get Python on my computer?
You can download directly from the Python organization. If you operate on
Mac or Linux, you probably already have some version of Python installed.
For science and data analysis stuff, I recommend Anaconda, which is what I
use. Anaconda is a Python distribution that comes pre-packaged with most of
the goodies that an engineer/scientist will want to use. Anaconda has a GUI
interface for ease of operation and comes with its own code editor, Spyder
that is relatively popular.

## What Python version do I use?
Short answer: 3.6 or later. I think the latest version as of typing this is 3.11. Long answer: it depends. A lot of 
older code was written in 2.7. There is a lot of current software that uses Python 2.7 still because it was used for so 
long. However, official support for Python 2.7 no longer exists. Only Python 3.0 and later is supported by the Python 
Foundation. Some packages still support their own code for Python 2.7, but that is slowly going away.
- Direct from Python: <https://www.python.org/>
- Anaconda: <https://www.anaconda.com/>

## What code editor do I use?
Code editors, also known as Interactive Development Environments (IDE) are
where you code, organize, and version control the code. At their most
simple, a code editor would be a text editor. You can edit code in Windows
notepad if you really want to, but you really don't want to.

### Pycharm
This is the one I've been using for awhile now, and I've become
pretty partial to it. It makes It easy to use virtual environments for specific
projects because it naturally organizes by project and helps set up a virtual environment with new projects. It has a 
very nice variable browser with some color coding. You can download Pycharm from jetbrain's (the company behind Pycharm)
website. It is a little more difficult to use than Spyder in the beginning, and I think that is because of its 
customizability. You can still manage virtual environments and packages through Anaconda's GUI when using Pycharm with 
Anaconda. I believe Anaconda also allows you to download Pycharm through their GUI.

### Spyder
This is the IDE distributed with Anaconda. I know several people that use Spyder and like it. Packages and environments 
can be managed and installed through Anaconda's GUI, but I don't think they can through Spyder (may be wrong). I believe
it also has Jupyter Notebook support.

### VSCode
I know next to nothing about VScode. It is used by many software developers, especially those that need to swap between 
multiple different languages.

### Jupyter Notebooks and Jupyter Labs
Jupyter Notebooks are pretty popular in the data science world. They are
very different than a typical code editor. I'd recommend looking up some
example videos or images if you are unfamiliar. They seem to promote
readability and understanding of the process over deploy-ability. The code
is normally passed as a Jupyter Notebook rather than a Python file/script.
Although, they are relatively easily converted from one to the other.
Jupyter Labs is a variation of Jupyter Notebooks that is more like a typical
code editor.

## What are packages and which ones are commonly used for scientists and engineers?
Packages are pre-coded functions another person or group has created and put
together in a way to be reused by other people. Packages are a huge reason behind Python's widely seen success. 
Python comes with many built in packages that are used frequently such as: os, sys, itertools, math, etc. Here are
some third party packages that are used frequently in science and
engineering applications.
- NumPy - Numerical Python. Some notable included features: arrays, matrix and
linear algebra computation, random distributions, basic statistics. Mostly
coded in Fortran and C under the hood or speed
- SciPy - Scientific Python. Built around NumPy. More statistical
distributions, more statistics functions, more math stuff.
- Matplotlib - The main plotting package for Python. Some similarities to
MatLab plotting. Plotting functions offer lots of tunability. 
- Pandas - Datframe capabilities. Work similarly to Python's dictionaries, but with many NumPy capabilities built in as 
methods of the Dataframe.
- Seaborn - Another plotting package that can provide very nice visualizations very easily, especially when using 
Pandas dataframes. Has less tunability than Matplotlib.

## Where does the name Python come from?
It's a Monty Python reference. 

## How should I format my code?
Nobody really asks this one, but I wish someone had told me earlier about the importance of coding style. I recommend
following the PEP-8 style guide as best you can. A good coding style helps promote readability, reproducibility, and
organization, especially on collaborative projects.
- <https://peps.python.org/pep-0008/>

## How do I learn Python?
I recommend learning the same way I did, which is to take some online class (there are a multitude of good ones) to 
help learn some basic syntax and execution. Then, start a project that you care about. Applying it to something you 
want to do is the best way to learn. Read other people's code as well. Read the documentation of packages you're using.
It may be tempting to copy and paste straight from stackoverflow or ChatGpt, but if you take the time to actually
understand what the code does, it will help you learn. Here are some good places to start learning Python.
- There is a tutorial on using Python in the Python documentation. Python along with many of its packages have very 
good documentation. 
  - <https://docs.python.org/3/tutorial/index.html>
- Codeacademy has a beginner friendly Python course that is free.
  - <https://www.codecademy.com/catalog/language/python>
- If you prefer book format, Automate the Boring Stuff by Al Sweigart is a popular choice. It is also free to read 
online.
  - <https://automatetheboringstuff.com/#toc>
- Python Crash Course by Eric Matthes is another popular book for beginners. This one is not freely available.
  - <https://ehmatthes.github.io/pcc/>
- Check out YouTube if you prefer a video format. There are a lot of good YouTube video tutorials available.
