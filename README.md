## Silence mypy with an empty .pyi file?

Is there a way to get mypy to complain about this?

```
$ pipenv run mypy src/
Success: no issues found in 1 source file
```

(It's looking at the empty `demo.pyi` file, not `demo.py`; this is [documented](https://mypy.readthedocs.io/en/stable/stubs.html) but seems highly undesirable.)

![](https://files.scoat.es/7gDnlrLk.png)

