# Python Tutorial
*Recommendations on getting started with Python.*

> As this project develops, I can upload samples files for topics as they are requested.

### Getting Python - Option 1
You probably want Python 3.5.x. I would only use Python 2.7.x if you need a 3rd party library that hasn't been written in Python 3 yet or if there was some other reason your system was limited to Python 2.7.
  * https://www.python.org/downloads/

### Getting Python - Option 2
If your goal is to use Python to explore data, or do reserach, I recommend installing Anaconda. This is an easy way to get both Python and a rich set of tools for data science and documentation preparation.
  * https://www.continuum.io/downloads
  
Other benefits to Anaconda:
  * A Learning section in the application that is very useful
  * Ability to download libraries for many of the advanced topics below

### Writing Python
Launch python at the command line and interact with it first. Most tutorials will expect you are doing this. Use the command prompt on Windows, or Terminal on Mac. If you are on Linux, I assume you know what you need to do here.

If you want an Interactive Development Environment to write, run, debug code, try this application from Microsoft - it's multi-platform, lightweight, and very nice.
  * https://code.visualstudio.com/?utm_expid=101350005-35.Eg8306GUR6SersZwpBjURQ.0&utm_referrer=https%3A%2F%2Fwww.google.com%2F

### Basic Python Understanding
The Python standard tutorial - uses the terminal or commandline, though it is written with a Unix/Mac focus
  * https://docs.python.org/3/tutorial/

A more interactive tutorial - has it's own editor - good first place to go before downloading anything
  * https://www.codecademy.com/learn/python 

The docs - when you want to know the specifics of the language and modules:
  * https://www.python.org/doc/

Dive Into Python lso a good tutorial - and has some interesting sections on unittesting (and test driven development, more generally)
  * http://www.diveintopython3.net
  * http://www.diveintopython3.net/unit-testing.html

### Data Science - Using Python with Jupyter/iPython
Jupyter notebooks blend concepts of a python interpreter with a documentation tool all in a web interface. This is available with the Anaconda installation  
  * https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-learn-data-science-python-scratch-2/
  * https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook#gs.bsR1O5g
  
iPython has similarities with Jupyter, but is typically run from the the Command Line or Terminal
  * https://ipython.org/install.html
  
### Combining R and Python
While this is a fairly advanced topic, if data science is an interest, R is probably an interest as well. ```RPy2``` allows one to leverage the power of R from Python, iPython, and Jupyter.
  * https://rpy2.bitbucket.io
  
For installation instructions, see here.
  * http://rpy2.readthedocs.io/en/version_2.8.x/overview.html#install-installation

You may notice the recommendation to use Docker containers. Docker is beyond the scope of this README, but does make obtaining pre-built deployments of this and other applications (e.g., databases) very simple.
  * https://www.docker.com

## Other advanced concerns

### Python with Amazon AWS
Depends on your needs, but useful information on the boto3 library used for interacting with AWS resources.
  * https://aws.amazon.com/sdk-for-python/

### Python on Google Cloud
If your preference is Google Cloud vs. Amazon...
  * https://cloud.google.com/appengine/docs/python/

### Database Development:
I won't cover the actual databases here, but these pages should give you some links to get you going, depending on what you need to do. It's rarely long before someone needs to get data in or out of a database. 
  * https://www.fullstackpython.com/databases.html
  * https://api.mongodb.com/python/current/

### Web Services
If RESTful services ever become a need or an interest
  * https://falconframework.org
  * http://www.django-rest-framework.org

Also - a tool for testing...
  * https://www.getpostman.com

### Web User Interface Development
If you ever wanted to create something web enabled with Python
  * https://www.djangoproject.com

There are others, but this is one I have used and like.
    
### Installation Tools
Not critical or necessary, but if you want to isolate your Python installation and the libraries you download, you can look at virtualenv. I will use this to help keep track of the libraries I need for a specific project.
  * https://virtualenv.pypa.io/en/stable/installation/

