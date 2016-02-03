cython-hidapi
=============

Description
-----------

A Cython interface to the HIDAPI from https://github.com/signal11/hidapi

Modified by @morinted to fix building universal binaries on OS X

It works on Linux, Windows XP and OS X.


Software Dependencies
---------------------

* Python (http://python.org/download/)
* Cython (http://cython.org/#download)
* hidraw or libusb and libudev on Linux

License
-------
cython-hidapi may be used by one of three licenses as outlined in LICENSE.txt.


Building
--------

1. Download cython-hidapi archive::

    $ git clone https://github.com/morinted/cython-hidapi.git --recursive
    $ cd cython-hidapi

2. Build cython-hidapi extension module::

    $ python setup.py build

3. Install cython-hidapi module into your Python distribution::

    $ [sudo] python setup.py install

4. Test install::

    $ python
    >>> import hid
    >>>

5. Test 32-bit::
    $ arch -32 python
    >>> import hid
    >>>

