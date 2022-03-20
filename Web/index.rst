.. CSS documentation master file, created by
   sphinx-quickstart on Fri Jan  1 15:15:56 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. role:: raw-html(raw)
   :format: html

===============================
Description
===============================

Interactive Web Interface
****************************************

The interactive Web Interface (IWI) provides connections between computational components and data input/analysis and visualization. An automated system is used to scrape forcing data from outside sources (API) such as tides, wind, atmospheric pressure, and wind waves. It generates boundary and forcing conditions needed by models. It also handles HPC scheduling, data analysis, data transfer between HPC and Web server.  

.. image:: images/automate_system/autosystem.png
   :width: 500px
   :height: 334px
   :align: right

*The system is being developed in the ESTCP project (TWL affected by storms and SLR).* 

Model Coupling System
****************************************

The Model Coupling System (MCS) links models in different scales and physics. The model components include the Coupled Ocean Atmosphere Wave Sediment Transport Modeling System (COAWST), Finite Volume Community Ocean Model (FVCOM), and in-house models, such as NearCoM, FUNWAVE-TVD, and NHWAVE. 

The following WIKI lists the in-house models and typical applications in Delaware Bay and adjacent nearshore regions.  

`CLICK to see an example of Interactive Flooding Maps (Norfork, 100-year storm, SLR 2100) <../../interactive_map/Flood_NF.html>`_
`CLICK to see an example of Interactive Bathymetry Maps (Inland Bays) <../../interactive_map/inlandbays_DEM.html>`_
`CLICK to see an example of Interactive Elevation Maps (Inland Bays) <../../interactive_map/eta_sample.html>`_

============
Wiki Content
============
.. toctree::
   :maxdepth: 2
   :caption: Contents:

   models
   applications

==================
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
