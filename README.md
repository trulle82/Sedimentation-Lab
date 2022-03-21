# Sedimentation-Lab

This lab is based on a [Jupyter Notebook](http://jupyter.org):
- `sedim.ipynb`

Author: Martin Trulsson<br>
E-mail: martin.trulsson@teokem.lu.se 

## Prerequisites

- No prior knowledge in Python is required, but familiarity with programming concepts is helpful.
- A laptop connected to the internet (eduroam, for example) and running Unix, MacOS, or Windows and with Anaconda installed, see below.

If you have little experience with Python or shell programming, the following two tutorials may be helpful:

- https://swcarpentry.github.io/shell-novice
- https://swcarpentry.github.io/python-novice-inflammation

## Preparation before the lab

1. Install [miniconda3](https://conda.io/miniconda.html).
2. [Download](https://github.com/gitesei/Sedimentation-Lab/archive/master.zip) the lab material
   (this github repository) and unzip.
3. Install and activate the `sedimlab` environment described by the file [`environment.yml`](/environment.yml)
   by running the following in a terminal:

   ```bash
   conda env create -f environment.yml
   source activate sedimlab
   ```
Instructions for Windows: 
1. Install [miniconda3](https://conda.io/miniconda.html).
2. [Download](https://github.com/gitesei/Sedimentation-Lab/archive/master.zip) the lab material (this github repository)
   and unzip.
3. Open the `anaconda prompt` from the start menu.
4. Navigate to the folder where the course material has been unzipped (_e.g._ using `cd` to change directory
   and `dir` to list files in a folder).
5. Install and activate the `sedimlab` environment described by the file [`environment.yml`](/environment.yml)
   by running the following in the `anaconda prompt`:

   ```bash
   conda env create -f environment.yml
   activate sedimlab
   ```
[Further Information](https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)

## How to launch the notebook

~~~ bash
jupyter-notebook sedim.ipynb
~~~
