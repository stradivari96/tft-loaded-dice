## modern-python-template
[![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/stradivari96/modern-python-template/blob/master/LICENSE)
[![codecov](https://codecov.io/gh/stradivari96/modern-python-template/branch/main/graph/badge.svg?token=NYKUYQR8ZG)](https://codecov.io/gh/stradivari96/modern-python-template)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

Inspired by https://github.com/TezRomacH/python-package-template

## Tools
* Gitmoji: https://gitmoji.dev/
* Black: https://black.readthedocs.io/en/stable/
* Isort: https://pycqa.github.io/isort/
* Poetry: https://python-poetry.org/

## Getting started
1. Install poetry

https://python-poetry.org/docs/#installation

2. Install dependencies
```
poetry install
poetry run pre-commit install
```

3. Run test
```
poetry run pytest --cov=my_package --cov-fail-under=80 --cov-report xml
```
