
.. note::

    nbodykit has recently upgraded to version 0.2.x, with significant changes
    to its API and user interface. The documentation for this new version is
    under active development. For the documentation for the previous version
    (0.1.x), please see http://nbodykit.readthedocs.io/en/0.1.11/.

.. image:: _static/nbodykit-logo.gif
   :width: 425 px
   :align: center

|

a massively parallel large-scale structure toolkit
===================================================

**nbodykit** is an open source project and Python package providing
a set of algorithms useful in the analysis of cosmological
datasets from N-body simulations and large-scale structure surveys.

Driven by the optimism regarding the abundance and availability of
large-scale computing resources in the future, the development of nbodykit
distinguishes itself from other similar software packages
(i.e., `nbodyshop`_, `pynbody`_, `yt`_, `xi`_) by focusing on :

- a **unified** treatment of simulation and observational datasets by
  insulating algorithms from data containers

- reducing wall-clock time by **scaling** to thousands of cores

- **deployment** and availability on large, super computing facilities

All algorithms are parallel and run with Message Passing Interface (MPI).

.. _nbodyshop: http://www-hpcc.astro.washington.edu/tools/tools.html
.. _pynbody: https://github.com/pynbody/pynbody
.. _yt: http://yt-project.org/
.. _xi: http://github.com/bareid/xi
.. _`NERSC`: http://www.nersc.gov/systems/

Index
-----

**Getting Started**

* :doc:`install`

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Getting Started

   install.rst

Get in touch
------------

- Report bugs, suggest feature ideas, or view the source code `on GitHub`_.

.. _on GitHub: http://github.com/bccp/nbodykit