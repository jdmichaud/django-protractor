0.8.2
=====
* Fix for django 1.9+

0.8.1
=====
* Fix for passing both suite and specs.
* Add live_server_url param when using the `protractor` command.
* Set `baseUrl` automatically for relative url use in protractor.

Thanks Loren M. Lang for all 3!


0.8
===
* Fix for python 3 compatibility. (Thanks David Black!)


0.7
===
* Add hook for protractor params to be passed from a test case.


0.6
===
* Add fixture support to `protractor` command. (Thanks Dmitry Mikhaylov!)


0.5
===
* Add live_server_url to the params passed into protractor


0.4
===

* Create a mixin to use with tests. This allows more easy creation of test
  cases and easy setup of initial data via fixtures or factories.


0.3
===

* Call django test runner's `setup_databases()`


0.2
===

* Stop swallowing protractor output
