# ds2002-fa26

Course notebooks for DS 2002, Fall 2026.

## Local setup

Use Python 3.13 (the version used to verify this environment):

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m ipykernel install --sys-prefix --name ds2002-fa26 --display-name "Python (ds2002-fa26)"
jupyter lab
```

In your editor, select `.venv/bin/python` as the Python interpreter and
**Python (ds2002-fa26)** as the notebook kernel. Activate the environment
with `source .venv/bin/activate` in each new terminal; use `deactivate` to exit.

The notebooks use pandas, NumPy, and Python's built-in SQLite support.
Their sample datasets are embedded, so no separate data download is needed.
