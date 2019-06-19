===============
pytest-molecule
===============

.. image:: https://img.shields.io/pypi/v/pytest-molecule.svg
    :target: https://pypi.org/project/pytest-molecule
    :alt: PyPI version

.. image:: https://img.shields.io/pypi/pyversions/pytest-molecule.svg
    :target: https://pypi.org/project/pytest-molecule
    :alt: Python versions

.. image:: https://travis-ci.org/pycontribs/pytest-molecule.svg?branch=master
    :target: https://travis-ci.org/pycontribs/pytest-molecule
    :alt: See Build Status on Travis CI

PyTest Molecule Plugin :: auto detects and runs molecule tests

----

This plugin enables pytest discovery of all molecule.yml files inside the codebase
and runs them as pytest tests.

Once you install pytest-molecule you should be able to just run `pytest` in order
to run molecule on all roles and scenarios.

Installation
------------

You can install "pytest-molecule" via `pip`_ from `PyPI`_::

    $ pip install pytest-molecule


Contributing
------------
Contributions are very welcome. Tests can be run with `tox`_, please ensure
the coverage at least stays the same before you submit a pull request.

License
-------

Distributed under the terms of the `MIT`_ license, "pytest-molecule" is free and open source software


Issues
------

If you encounter any problems, please `file an issue`_ along with a detailed description.

.. _`MIT`: http://opensource.org/licenses/MIT
.. _`file an issue`: https://github.com/ssbarnea/pytest-molecule/issues
.. _`pytest`: https://github.com/pytest-dev/pytest
.. _`tox`: https://tox.readthedocs.io/en/latest/
.. _`pip`: https://pypi.org/project/pip/
.. _`PyPI`: https://pypi.org/project