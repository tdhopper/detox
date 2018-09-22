[![Build Status](https://travis-ci.org/tox-dev/detox.svg?branch=master)](https://travis-ci.org/tox-dev/detox)
[![Latest Version on PyPI](https://badge.fury.io/py/detox.svg)](https://badge.fury.io/py/detox)
[![Supported Python Versions](https://img.shields.io/pypi/pyversions/detox.svg)](https://pypi.org/project/detox/)

**Please note: this project needs some serious TLC - see [this issue](https://github.com/tox-dev/detox/issues/27).**

# What is detox?

detox is the distributed version of [tox](https://pypi.org/project/tox/).  It makes efficient use of multiple CPUs by running all possible activities in parallel.  It has the same options and configuration that tox has so after installation can just run:

    detox

in the same way and with the same options with which you would run `tox`, see the [tox home page](http://tox.readthedocs.io) for more info.

Additionally, detox offers a `-n` or `--num` option to set the number of concurrent processes to use.
