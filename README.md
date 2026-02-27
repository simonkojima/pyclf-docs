# pyclf-docs
## docs generation

### Requirements for docs generation

Install pyclf first.

```
pip install sphinx pydata-sphinx-theme sphinx-multiversion sphinx-gallery numpydoc
```

1. Run following in docs

```

sphinx-apidoc -f -o ../docs/source ../pyclf && make html

```

2. Run following in pyclf root

```

sphinx-build -b html docs/source ~/git/pyclf-docs/latest

```