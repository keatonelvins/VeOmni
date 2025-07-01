# VeOmni documents

## Build the docs

```bash
# Install dependencies.
cd docs
uv venv
source .venv/bin/activate
uv pip install -r requirements-docs.txt

# Build the docs.
make clean
make html
```

## Open the docs with your browser

```bash
python -m http.server -d _build/html/
```
Launch your browser and open localhost:8000.
