# Introduction to using Earth data with Python

### Instructor: [Rebekah Esmaili](http://www.rebekahesmaili.com)

---

This workshop will cover:

* How access Earth datasets
* Importing netCDF files, a scientific data formats, using the xarray package
* Creating simple graphics with the Matplotlib package
* Creating a map using the Cartopy package

This code is interactive! Click:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/modern-tools-workshop/technica-workshop-2021/HEAD)

---

## Prerequisites
A basic understanding of Python. A basic understanding of jupyter notebooks is recommended. You will need to know how to import packages, subset data, and use matplotlib, numpy and pandas.
---

## Installation requirements

"I am really new to Python!"

* I recommend launching binder, which is a "cloud version" of this course. No installation required!
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/modern-tools-workshop/AGU-python-workshop-2020/HEAD)

* Need help with Binder? Video tutorial on [YouTube](https://youtu.be/3BrfFe4HsAw).

"I have used Python before!"

* If you wish to run the examples locally, I recommend installing [Anaconda](https://www.anaconda.com/products/individual).
* Need help installing Anaconda? Video tutorial on [YouTube](https://youtu.be/zxSQCXXvOIM).
* Download the contents of the [GitHub repository](https://github.com/modern-tools-workshop/AGU-python-workshop-2020) to your computer.
* Launch Jupyter Notebooks from the Anaconda Navigator. This will open a window in your default browser. Navigate to the folder that contains the notebooks (*.ipynb) and click on the tutorial for the day.
* New to Jupyter? Here's a video tutorial on [YouTube](https://youtu.be/gmMCuR9JPpY).
* Additional packages:
  * Launch the Anaconda Prompt (Windows) or Terminal (MacOS/Linux). Then copy/paste and hit enter:
    ```
    conda install -c conda-forge cartopy
    ```
  * If there are no errors, then you are set-up!
  * Alternatively, if you are familiar with environments, you can use the environments.yml to install the necessary packages.

I *do not* recommend:
* Using Python on a remote server for this tutorial (I cannot help troubleshoot)
* Using your operating system's Python or a shared Python installations unless you are advanced!

---
## Course Philosophy

* Increase accessibility of satellite data and analysis
* Teach Python using practical examples and real-world datasets
* Promote reproducible and transparent scientific research

## Other Resources

* Learn more about other Earth datasets via [The NOAA Physical Sciences Lab](https://www.psl.noaa.gov/data/gridded/), [NASA EarthData](https://earthdata.nasa.gov/) and [NOAA NCEI](https://www.ncei.noaa.gov/)
* Learn more about [Python for Atmosphere and Ocean Scientists](https://carpentries-lab.github.io/python-aos-lesson/) using Software Carpentry lesson plans.
* I have a longer workshop on [Python for Earth Science with Rebekah](https://youtube.com/playlist?list=PLlcgQ3Rl-9fR4oOmfeKPKHuk2Lj57bNJy)
* Request copy of my book [Earth Observation using Python](https://www.wiley.com/en-us/Earth+Observation+using+Python%3A+A+Practical+Programming+Guide-p-9781119606888) through inter library loan from your university library!
