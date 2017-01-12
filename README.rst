DDBCLI: A DynamoDB command line interface with JSON I/O
=======================================================

Installation
------------
::

    pip install ddbcli

Synopsis
--------

Use ``aws configure`` to set up your AWS command line environment.

.. code-block:: bash

    ddb get TABLE_NAME HASH_KEY
    DYNAMODB_TABLE=mytable ddb get HASH_KEY

    ddb put mytable '{"key": "foo", "data": "xyz"}' '{"key": "bar", "data": "xyz"}'
    ddb scan mytable

Authors
-------
* Andrey Kislyuk

Links
-----
* `Project home page (GitHub) <https://github.com/kislyuk/ddbcli>`_
* `Documentation (Read the Docs) <https://ddbcli.readthedocs.io/en/latest/>`_
* `Package distribution (PyPI) <https://pypi.python.org/pypi/ddbcli>`_
* `Change log <https://github.com/kislyuk/ddbcli/blob/master/Changes.rst>`_

Bugs
~~~~
Please report bugs, issues, feature requests, etc. on `GitHub <https://github.com/kislyuk/ddbcli/issues>`_.

License
-------
Licensed under the terms of the `Apache License, Version 2.0 <http://www.apache.org/licenses/LICENSE-2.0>`_.

.. image:: https://img.shields.io/travis/kislyuk/ddbcli.svg
        :target: https://travis-ci.org/kislyuk/ddbcli
.. image:: https://codecov.io/github/kislyuk/ddbcli/coverage.svg?branch=master
        :target: https://codecov.io/github/kislyuk/ddbcli?branch=master
.. image:: https://img.shields.io/pypi/v/ddbcli.svg
        :target: https://pypi.python.org/pypi/ddbcli
.. image:: https://img.shields.io/pypi/l/ddbcli.svg
        :target: https://pypi.python.org/pypi/ddbcli
.. image:: https://readthedocs.org/projects/ddbcli/badge/?version=latest
        :target: https://ddbcli.readthedocs.io/
