# Python configuration

## Package Manager
I am using uv as a package manager so please use the uv commands for running applications and tests.


## Python Version
I am using python version 3.13.
Make sure to use the correct type hints and language features.
E.g. do not use from typing import List, instead use list directly.


## Running tests

For tests please use this command to also create a coverage report.
```uv run pytest tests --cov=src --cov-report=html -v```


## Linting and Code Quality
I use an extensive pre-commit configuration for that.
pre-commit run --all-files is the command for making sure everything is correct.


## Formatting
Please do not create tabs in empty lines.

