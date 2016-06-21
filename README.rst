===============================
Python Mini Racer
===============================

.. image:: https://img.shields.io/pypi/v/py_mini_racer.svg
        :target: https://pypi.python.org/pypi/py_mini_racer

.. image:: https://img.shields.io/travis/sqreen/py_mini_racer.svg
        :target: https://travis-ci.org/sqreen/py_mini_racer

.. image:: https://readthedocs.org/projects/py_mini_racer/badge/?version=latest
        :target: https://readthedocs.org/projects/py_mini_racer/?badge=latest
        :alt: Documentation Status


Minimal, modern embedded V8 for Python.

* Free software: ISC license
* Documentation: https://py_mini_racer.readthedocs.org.

Features
--------

* TODO

Credits
---------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-pypackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

Build
--------

You need to build v8 first by hand, go to "py_mini_racer/ffi" first, then launch
the "v8_build.py" python script:

.. code:: bash

  python v8_build.py


Then from the root directory of this repository, create a wheel with:

.. code:: bash

    python setup.py bdist_wheel