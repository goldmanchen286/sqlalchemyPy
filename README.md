# SQLAlchemy Tutorial

The SQLAlchemy tutorial, using notebooks!

This content is adapted from <https://github.com/sqlalchemy/sqlalchemy/tree/master/doc/build/tutorial>, using sqlalchemy v1.4.53

- Convert RST to MyST with [rst-to-myst](https://github.com/executablebooks/rst-to-myst)
  - `rst2myst convert -R doc/build/tutorial/*`
- Remove content above top-header in each file
- Replace inter-sphinx references

## Development

To build the documentation, simply run [tox](https://tox.readthedocs.io/en/latest/).

## TODO

- targets uses `-` but refs used `_` and myst-parser didn't like this.
- `rst-class` in `eval-rst` causes failure, unhandled pending node.
- Better code hiding (title dropdown)
