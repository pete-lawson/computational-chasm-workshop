# Johns Hopkins Computational Chasm Workshop
Workshop materials and additional resources for the __Crossing the Computational Chasm - Infrastructure Agnostic Data Visualization using Jupyter Notebooks__ workshop presented at Johns Hopkins University September 1st, 2020.

### Slides for the Workshop

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pete-lawson/computational-chasm-workshop/master?filepath=computational_chasm_workshop.ipynb)

### Deploy the Interactive Data Visualization in Altair Tutorial

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pete-lawson/computational-chasm-workshop/blob/master/interactive_data_visualization_with_altair.ipynb)

## Table of Contents

1. [Workshop Learning Objectives](#objectives)
2. [Deploying an Interactive Notebook](#deploy)
3. [Additional Resources](#resources)
4. [License](#license)


<a name="objectives"/>

## Workshop Learning Objectives
This workshop introduces `Jupyter Notebooks` as a tool to perform interactive
data visualization in way that is consistent, whether you are running it on a
laptop, a high-performance computer like MARCC, or a distributed
cluster-computing environment like Apache Spark. Additionally this workshop
introduces a workflow for creating reproducible and interactive Jupyter
Notebooks with a digital object identifier (DOI). Finally, this workshop
motivates the use of Jupyter Notebooks through interactive data visualization
with `Altair`.

1. Understand what `Jupyter Notebooks` are, how they are used, and when it is appropriate to use a `Jupyter Notebook` for data visualization and analysis.
2. Understand how `Jupyter Notebooks` can be used for scaling data visualization and analysis.
3. Understand how to deploy a `Jupyter Notebook` using a hosted service like Binder or Google Colaboratory.

<a name="deploy"/>

## Deploying an Interactive Jupyter Notebook

A number of services exist for deploying `Jupyter Notebooks` on the cloud for
free. A non-exhaustive list of services is highlighted below, with services
selected that stand-out due to relevant features, such as collaboration,
reproducibility, and available computational resources.
<a name="resources"/>

[<img src="figures/binder_logo.svg">](http://mybinder.org/)

[Binder](https://mybinder.org/) allows you to launch an interactive `Jupyter Notebook` instance. It does
this by reading from a configuration file stored in the repository you are
launching, either `environment.yml` if you are using Anaconda Python, or
`requirements.txt` if you are just using the `pip` Python package manager. This
is a benefit over other services like Google Colaboratory because it ensures
your Python environment is reproducible, that is you will be installing the same
packages whether you run it on your laptop, an HPC, or Binder.

#### Supported Languages
All languages supported by Jupyter.

#### Performance
2 GB of RAM is available for Binder instances, with no explicit limit on disk usage, although they ask out of consideration for the free and open nature of the service that you restrict data files to no more than a few hundred megabytes. 

#### Availability
Binder sessions shutdown after 20 minutes of activity, but if in active use can be run for 12 hours. Up to 100 users can simultaneously access a Binder instance for a given repository. 

[<img src="figures/cocalc_logo.png">](http://cocalc.com/)


[<img src="figures/colab_logo.jpeg">](http://colab.research.google.com/)


## Additional Resources 

The [Jupter Notebook](https://jupyter.org/index.html) is a an open-source,
web-based application that can be run locally, or shared online, and allows you
to create and share documents (notebooks) that contain live code,
visualizations, narrative text, and mathematical equations. They provide a
wonderful way of documenting and sharing your research with the world.

### Sharing your Jupter Notebook. 
These notebooks are rendered natively in Github so you can share them with
others. They can be managed under versioning control using Git, and shared on
[GitHub](https://github.com/), a cloud-based hosting service that allows you to
manage and share your Git repositories. For more information on versioning
control and how to create a Git project and share it with the world follow the
[Software Carpentries tutorial on Version Control with Git and
Github](http://swcarpentry.github.io/git-novice/).

### Jupyter Notebook Shortcuts
To see a list of keyboard shortcuts, in a running Jupyter notebook first enter
command mode by hitting `esc`. Then press the `h` key to display the help menu,
which will display common operations and their corresponding shortcuts. These
shortcuts are operating system dependent, so if you call the `h` prompt from
Windows your shortcuts will look different than if you call `h` from a Mac.

### Presentations with Jupyter Notebook
Jupyter is extensible, that is you can add extensions to it in order to enhance
its functionality. One such extension is the
[RISE](https://rise.readthedocs.io/en/maint-5.6/) extension. __RISE__ stands for
__Reveal.js -- Jupyter/IPython Slideshow Extension__. This extension allows you
to toggle between a normal notebook instance and an interactive presentation
mode. The introduction to Data Visualization presentation at the beginning of
the workshop was simply a Jupyter Notebook in RISE mode.

[![Reveal.js](https://miro.medium.com/max/500/0*7l6Q6WgP4_DN_VLI.png)](https://rise.readthedocs.io/en/maint-5.6/)

To explore __RISE__ without installing it yourself, deploy a Binder with this
workshops slides:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pete-lawson/computational-chasm-workshop/master?filepath=computational_chasm_workshop.ipynb)

This will start a `Jupyter Notebook` instance on Binder, and the presentation
will begin automatically. To exit or enter the slideshow either use the button
(“Enter/Exit Live Reveal Slideshow”) in the toolbar, or use the keyboard shortcut `Alt-r`. 

To navigate a __RISE__ presentation use `SpaceBar` to go forward, and
`Shift-SpaceBar` to go backward, or you can use the visual controller in the
slideshow right bottom corner. To hide the interface overlay (or bring it back after being hidden) use the keyboard shortcut `,`.  

For more information about using the __RISE__ presentation plugin in Jupyter
Notebook, please refer to the [RISE
documentation](https://rise.readthedocs.io/en/stable/index.html)

<a name="license"/>

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

