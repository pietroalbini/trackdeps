~~~~~~~~~
trackdeps
~~~~~~~~~

**Warning:** this project is not maintained anymore, but there are a bunch of
alternatives around the web if you need them.

----

trackdeps is a Python dependencies tracking library, written in Python 3. It
provides a list of dependencies used by your projects, which ones needs to be
updated in requirements files and the latest releases.

You can use it both as a library for other projects, or to directly generate
reports with the built-in command-line utility. The whole project is released
under the MIT license.

Please refer to the documentation if you need more information about how to
use trackdeps.

Installation
============

In order to install trackdeps, just download it with pip::

   $ pip install trackdeps

If you want to install from source, clone this repository, make sure you have
`virtualenv`_ and `invoke`_ installed, and then execute this command::

   $ invoke install

.. _virtualenv: https://virtualenv.pypa.io
.. _invoke: http://www.pyinvoke.org
