daemoncxt
=========

Library to implement a well-behaved Unix daemon process

Provides DaemonContext (see PEP 3143 and multiple discussions on the net).

Example:

    from daemoncxt import DaemonContext

    from spam import do_main_program

    with DaemonContext():
        do_main_program()


Installation
------------

pip install daemoncxt


Links
-----
This version is an unofficial mirror of 

https://github.com/arnaudsj/python-daemon

and

https://pypi.python.org/pypi/python-daemon/


