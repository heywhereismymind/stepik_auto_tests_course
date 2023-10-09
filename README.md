# Install and run project

python -m venv .venv
./.venv/Scripts/Activate.ps1 (for Windows)
pip install -r requirements.txt
pytest -v --tb=line --language=en -m need_review

