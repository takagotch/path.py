### path.py
---
https://github.com/jaraco/path.py

```py
from path import Path
d = Path('/home/guido/bin')
for f in d.files('*.py'):
  f.chomd(0o755)
for f in d.files('*.py'):
  f.chomod(0o755)
with Path("somewhere"):
foo_txt = Path("bar") / "foo.txt"
```

```
pip install path.py
pip install https://github.com/jaraco/path.py.git
```

```
```
