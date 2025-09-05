# Edin

A Python project for data analysis and machine learning.

## Features

- Data processing with pandas and numpy
- Machine learning with scikit-learn
- Statistical analysis with scipy
- Data visualization with matplotlib and seaborn
- HTTP client capabilities with httpx

## Installation

This project uses [uv](https://docs.astral.sh/uv/) for dependency management.

```bash
# Install dependencies
uv sync

# Install with dev dependencies
uv sync --group dev
```

## Development

```bash
# Activate virtual environment
source .venv/bin/activate

# Install dev dependencies
uv sync --group dev

# Start Jupyter kernel (if using notebooks)
python -m ipykernel install --user --name edin
```

## Usage

```python
import pandas as pd
import numpy as np
from sklearn import datasets

# Your code here
```

## Requirements

- Python >=3.12
- See `pyproject.toml` for full dependency list