juka-kernel
===========

``juka-kernel`` allows Juka to be run in Jupyter notebook

Installation
------------
NOTE: PATH to Juka must be defined, make sure it is defined prior to installing the kernel

To install ``juka-kernel`` from this repository::

    python -m juka-kernel.install

Install from PyPi::

    pip install juka-kernel

Using the Juka kernel
---------------------
**Notebook**: The *New* menu in the notebook should show an option for an Juka notebook.

**Console frontends**: To use it with the console frontends, add ``--kernel juka`` to
their command line arguments.

Uninstall Juka Kernel
---------------------
Run the following command to uninstall ``juka-kernel``::

    jupyter kernelspec uninstall juka


Compile Juka .whl (Development Only)
------------------------------------

Run the following command::

    python -m build

Upload to PyPi (Internal Use Only)
-----------------------------------

Run the following command::

    python -m twine upload dist/*
