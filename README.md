# Instructions

- `python -m venv .venv`
- `source .venv/bin/activate`

- `source [venv directory]/bin/activate`
- `pip install -r requirements.txt`
- `pytest`
- `pytest --cov --cov-branch --cov-report=xml`

Add Codecov token: CODECOV_TOKEN in GitHub repo:

- Settings > Secrets and variables > Actions > New Repository Secret
