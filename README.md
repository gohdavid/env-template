# env-template
```
package/
├─ __main__.py
├─ plot.py
```

Rename the package.

```
conda env create -f environment.yml
poetry init --python=~3.9
```

Then `poetry add`. Python 3.9 prevents scipy error in Mac M1.