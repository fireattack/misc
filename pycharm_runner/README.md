PyCharm Runner: Run and Debug Python Modules in PyCharm
=======================================================

PyCharm 2016 run & debug configurations support python scripts only, and not python modules (i.e. `python -m mypackage.mymodule`). This little script solves the problem by dynamically importing the desired module.

Instructions
------------

* Copy `pycharm_runner.py` to a location of your choosing.
* Create a new run configuration in PyCharm.
* Fill in the full path of `pycharm_runner.py` in the Script text field.
* Fill in the fully qualified entry-point-style name of your target in the Script Parameters field, e.g. `package.module:function`.
* All additional parameters in the Script Parameters field will be passed to your target.
* Run & enjoy.

