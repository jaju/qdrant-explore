## Dev setup on checking out the repository

Assuming you have `virtualenv` available locally, run the following steps. If you choose any other mechanism to manage your Python installation, please modify accordingly.
(Note: python-lsp-server is optional)

```bash
virtualenv -p python3.11 .venv/qdrant
source .venv/qdrant/bin/activate
pip install --upgrade pip poetry python-lsp-server
```

### FYI
The following was done to set up the initial repository, and is only here for the record.
```bash
poetry init (once only when creating this repo - not required if checking out the repository)
```

### Install packages
```bash
poetry install
```
