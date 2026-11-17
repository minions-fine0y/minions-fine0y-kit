# minions-fine0y-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m minions_fine0y_kit.cli --help
```

```python
from minions_fine0y_kit.core import MinionsFine0yTool

tool = MinionsFine0yTool()
print(tool)
```

## Layout

```
minions_fine0y_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 minions-fine0y
