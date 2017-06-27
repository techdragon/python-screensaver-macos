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
        | |landscape|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-screensaver-macos/badge/?style=flat
    :target: https://readthedocs.org/projects/python-screensaver-macos
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/python-screensaver-macos.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/python-screensaver-macos

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/python-screensaver-macos?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/python-screensaver-macos

.. |requires| image:: https://requires.io/github/techdragon/python-screensaver-macos/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/python-screensaver-macos/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/techdragon/python-screensaver-macos/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/python-screensaver-macos

.. |landscape| image:: https://landscape.io/github/techdragon/python-screensaver-macos/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/python-screensaver-macos/master
    :alt: Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/screensaver-macos.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/screensaver-macos

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/python-screensaver-macos/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/python-screensaver-macos/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/screensaver-macos.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/screensaver-macos

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/screensaver-macos.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/screensaver-macos

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/screensaver-macos.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/screensaver-macos


.. end-badges

MacOS screensaver management library.

* Free software: BSD license

Installation
============

::

    pip install screensaver-macos

Documentation
=============

https://python-screensaver-macos.readthedocs.io/

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
