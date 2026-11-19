# plenarymouse-9g-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m plenarymouse_9g_kit.cli --help
```

```python
from plenarymouse_9g_kit.core import Plenarymouse9gTool

tool = Plenarymouse9gTool()
print(tool)
```

## Layout

```
plenarymouse_9g_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 plenarymouse-9g
