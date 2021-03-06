pyansys
=======

This Python module allows you to to extract data from ANSYS files and to display them if VTK is installed.  Supports result ``(.rst)``, mass and stiffness ``(.full)``, and block archive ``(.cdb)`` files.
 
.. image:: ./images/rotor.jpg

Contents
========

.. toctree::
   :maxdepth: 2
   
   examples
   loading_results
   loading_km


Installation
------------
Installation through pip::

    pip install pyansys

You can also visit `PyPi <http://pypi.python.org/pypi/pyansys>`_ or `GitHub <https://github.com/akaszynski/pyansys>`_ to download the source.

Dependencies:
- ``numpy``
- ``cython``
- ``vtkInterface``
- ``vtk`` (optional)

Minimum requirements are numpy to extract results from a results file. To convert the raw data to a VTK unstructured grid, VTK 5.0 or greater must be installed with Python bindings.

See `Install VTK <http://vtkinterface.readthedocs.io/en/latest/installation.html>`_ for details instructions for installing VTK.

License
-------
This module is licensed under the MIT license.  See the license file for more details.
