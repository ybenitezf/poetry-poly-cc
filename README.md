# poetry-poly-cc

A poetry polylith cookiecutter template

Use as:

```shell
cookiecutter https://github.com/ybenitezf/poetry-poly-cc.git
```

Answer the questions and ready to go. Read the README.md included for prerequisites.

## What is included

1. Poetry is configured to create the virtualenv in the project folder (see `poetry.toml`)
2. [pytest](https://docs.pytest.org/en/stable/) is added as a test dependency, also includes some goodies for pytest: `pytest-mock`, `pytest-cov` and `pytest-asyncio`
3. `pre-commit` & `ruff` as dev dependencies.
4. The support scripts `build-packages.sh` and `update-locks.sh`
5. Recommended vscode extensions
