StackTraces
===========

|Donate| |PyPI Version| |PyPI License| |PyPI Format| |PyPI Status|

Stack and stats tracer for multi-threaded applications.

Periodically dump stack traces and stats of all active threads of the
running process into a given file in intervals of time.


Installation
~~~~~~~~~~~~

.. code:: shell

    pip install stacktraces


Usage
~~~~~

.. code:: python

    from stacktraces import StackTraces
    tracer = StackTraces('/tmp/stacktraces{ext}', traceback_interval=5, stats_interval=10)
    tracer.start()
    # Do something with multi-threading here...
    tracer.stop()


License
~~~~~~~

The MIT Licence

.. |Donate| image:: https://img.shields.io/badge/Donate-PayPal-green.svg
   :target: https://www.paypal.me/Kronuz/25
.. |PyPI Version| image:: https://img.shields.io/pypi/v/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
.. |PyPI License| image:: https://img.shields.io/pypi/l/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
.. |PyPI Wheel| image:: https://img.shields.io/pypi/wheel/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
.. |PyPI Format| image:: https://img.shields.io/pypi/format/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
.. |PyPI Python Version| image:: https://img.shields.io/pypi/pyversions/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
.. |PyPI Implementation| image:: https://img.shields.io/pypi/implementation/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
.. |PyPI Status| image:: https://img.shields.io/pypi/status/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
.. |PyPI Downloads| image:: https://img.shields.io/pypi/dm/stacktraces.svg
   :target: https://pypi.python.org/pypi/stacktraces
