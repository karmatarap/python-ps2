========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-ps2/badge/?style=flat
    :target: https://readthedocs.org/projects/python-ps2
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/karmatarap/python-ps2.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/karmatarap/python-ps2

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/karmatarap/python-ps2?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/karmatarap/python-ps2

.. |requires| image:: https://requires.io/github/karmatarap/python-ps2/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/karmatarap/python-ps2/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/karmatarap/python-ps2/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/karmatarap/python-ps2

.. |version| image:: https://img.shields.io/pypi/v/ps2.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/ps2

.. |commits-since| image:: https://img.shields.io/github/commits-since/karmatarap/python-ps2/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/karmatarap/python-ps2/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/ps2.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/ps2

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/ps2.svg
    :alt: Supported versions
    :target: https://pypi.org/project/ps2

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/ps2.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/ps2


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install ps2

Documentation
=============


https://python-ps2.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
