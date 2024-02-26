# python-projects
Tips for Python projects

## Assumptions

* Reasonable familiarity with Python language

* If using an IDE it's VS Code

* Using a current or recent version of Python

* Using, or familiar with, Linux or MacOS command line

## Virtual environments

Create a virtual environment in the current directory.

```
$ python3 -m venv .venv
```


Same, but using Pipenv

```
$ mkdir .venv
$ touch Pipfile
$ pipenv install
```

Or just ```pipenv install``` if you do not want the .venv directory in your project directory. N.B. if it isn't there, then VS Code will not automatically detect it.
