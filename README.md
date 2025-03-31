This is my last poetry project, and I hope it's also yours :smile:

It transforms a pyproject.toml from `poetry` to `uv`

How to use it:

To check what will be the outcome
```sh
uvx --python 312 --with=git+https://github.com/leiserfg/poetry-uvify poetry uvify
```

To really apply it.

```sh
uvx --python 312 --with=git+https://github.com/leiserfg/poetry-uvify poetry uvify -r

```


Note: We are fixing python version in the command to avoid rebuilding one of the dependencies of poetry.
