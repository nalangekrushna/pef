pef_krushna_krushna
===

.. image:: https://img.shields.io/pypi/l/pef_krushna.svg
    :target: https://pypi.python.org/pypi/pef_krushna

.. image:: https://img.shields.io/pypi/v/pef_krushna.svg
    :target: https://pypi.python.org/pypi/pef_krushna

.. image:: https://img.shields.io/pypi/pyversions/pef_krushna.svg
    :target: https://pypi.python.org/pypi/pef_krushna

Enhancement for pip uninstall command, that it removes all dependencies of an uninstalled package.

☤ Quickstart
------------

Uninstall package, e.g, qu:

::

    $ pef_krushna qu -y

Uninstall multiple packages, e.g, qu, gy:

::

    $ pef_krushna qu gy -y

☤ Installation
--------------

You can install "pef_krushna" via pip from `PyPI <https://pypi.python.org/pypi/pef_krushna>`_:

::

    $ pip install pef_krushna
	
☤ Usage
-------

::

    $ pef_krushna --help
    Usage: pef_krushna [OPTIONS] [PACKAGES]...

      Uninstall packages with all its dependencies.

    Options:
      -y, --yes  Don't ask for confirmation of uninstall deletions.
      --help     Show this message and exit.
