.. nbsphinx-rtd-test documentation master file, created by
   sphinx-quickstart on Wed Sep 28 16:20:38 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to a Collection of Tutorials for the Python Package `tropy`
==================================================================
Intro
-----
This is a set of tutorial notebooks which aim to partially describe the functionality of the python package `tropy` which I started to develop at TROPOS since 2011. It contains a rather diverse collection of utility functions for which I did not found an appropriate solution in an existing package. The python landscape has considerably changed - hence some of the tools are somehow outdated, some functions are now covered by established package collections. 

All tutorials are available as jupyter notebooks.

Tools for IO
------------
Function have been written to ease input of certain obervational or model-simulated fields available at TROPOS. These function included data from

* **observations from Meteosat SEVIRI**
  :doc:`with the 'MSevi' class <Meteosat_SEVIRI_data_class>`  and
  :doc:`make RGBs with the 'MSeviRGB' class <Meteosat_SEVIRI_RGBs>`


* **observations from the DWD radolan Radar Composite**
  :doc: `with the Radolan class TBD` 


Tools for Plotting
------------------
Some helper functions to make typical task in plotting easier.

* **plotting shades with a non-linear (discrete) colormap**
  :doc:`with the 'shaded' module <Shaded_Plots_with_Nonlinear_Colormaps>`
* **using some special colormaps**
  :doc:`with the 'colormaps' module <Plots_with_Self-defined_Colormaps>` 
* **adding meta data to PNG Files**
  :doc:`with the 'meta2png' module <Adding_Meta-Data_to_PNG_File>` 


Tools for Analysis
------------------
Some helper functions to make special tasks in data analysis easier.

* **rank transformations and histogram matching**
  :doc:`with the 'statistics' module <Rank_Transformation_and_Histogram_Matching>`



.. toctree::
   :maxdepth: 1 
   :hidden:
   :caption: Data IO
   
   Meteosat_SEVIRI_data_class
   Meteosat_SEVIRI_RGBs

.. toctree::
   :maxdepth: 1 
   :hidden:
   :caption: Plotting

   Shaded_Plots_with_Nonlinear_Colormaps
   Plots_with_Self-defined_Colormaps
   Adding_Meta-Data_to_PNG_File
   
.. toctree::
   :maxdepth: 1 
   :hidden:
   :caption: Analysis

   Rank_Transformation_and_Histogram_Matching
