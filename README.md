# 🍪 Minimal python package template

Minimal [cookicutter](https://github.com/cookiecutter/cookiecutter) template for a python package.
It use :

-   [`setuptools`](https://setuptools.pypa.io/en/latest/) for packaging
-   [`setuptools_scm`](https://github.com/pypa/setuptools_scm/) for managing the package version thanks to git.
-   [`build`](https://github.com/pypa/build) to build your package
-   [`twine`](https://twine.readthedocs.io/en/stable/) to upload it to [pypi](https://pypi.org/)

## Getting started

1. `cookiecutter https://github.com/h4c5/cookie-python-minimal`
2. `cd your_project`
3. `git init` (necessary because of `setuptools_scm` that will manage the package version)
4. `pip install -e .[dev]`
5. ✨ developing ✨
6. `python -m build`
7. `twine upload -r testpypi`
