# linkedin_crawl_api

Linkedin data API crawl

## Installation

Python >= 3 required

To install the package with the latest changes in this repo
after you might have created your virtual environment (venv)

```bash
make install
```

To install PyPI version:

```bash
pip3 install linkedin-api~=2.0.0a
```

### how to start it

```
python3 helo.py

```

## Documentation

For a complete reference documentation, see the [documentation website](https://linkedin-api.readthedocs.io/).

## Overview

This project attempts to provide a simple Python interface for the Linkedin API.
you can check the below link to get some clue, but not absolutely the same

https://developer.linkedin.com/

### Development installation

1. Create a `.env` config file. An example is provided in `.env.example` - you include at least all of the settings set there.
2. Using pipenv...

   ```bash
   pipenv install --dev
   pipenv shell
   ```

### tests

```bash
python -m pytest tests
```
