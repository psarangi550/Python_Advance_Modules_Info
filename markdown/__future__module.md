# <ins> __futute__ module in python </ins> #

- we can import the `anonotations` from the `__future__` module which can `convert` the `type annotation` into the `string format` sin order to avoid any error in case of the `type hinting`

- we can see the `documentation of a module` by using the commmand as `python3 -m pydoc <module name>` so for the future module we can use it as `python -m pydoc __future__` which will show the doc for the `__future__` module in that case

- most of the `flag` of the `__future__` module been used for `migration between` the `python 2.X and 3.X`

- we can import the `print_function` from the `__future__` module in `python 2.7` and use the `print` as the `function` rather than `statements`

- when we use the `python 2.7` then we can say that `type('')` is `<class str>` by default but if we want to make it as unicode literal then we can use it as `from __future__ import unicode_literals`

- similarly we can use the `with_statement` in the python `2.7`  using the `from __future__ import with_statement`

- if we want to use the `generator` then we can use the `from __future__  import generator ` in order to use the `generator`

- we can use the `from __future__ import barry_as_FLUFL` to use the `<>` as `not equal operator` in the `python 2.7` which does not work in case of `python 3.0`

- for stopping the `generator` we can use the `StopIteration Error Exception` but now we can use the `GeneratorExit` exception to stop the `generator` after python 3.7

- the `__future__` import should be done before any code in the `module`

- but only exception is the `docstring` which can be mentioned before the `__future__` module in  python file /module 

- we can run the `python file` with the `doc string` using the command as `python3 -i <module/file name>`

- then using the `__doc__` we can fetch the `docstring` for the same 

