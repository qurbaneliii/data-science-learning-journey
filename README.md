# Data Science Learning Journey

A small collection of Jupyter notebooks for practicing Python fundamentals and basic data visualization.

## Overview

This repository is a learning journal aimed at building comfort with core Python concepts (variables, data types, collections, loops/conditionals) and introductory plotting with NumPy + Matplotlib. It’s best suited for beginners working through exercises in a notebook environment (VS Code or Jupyter).

## Key Features

- Python fundamentals exercises (arithmetic, strings, type conversion)
- Working with lists/sets and basic algorithms (min/max, sorting, swapping, reversing)
- Control flow practice (loops, conditionals)
- Small practice “projects” inside notebooks (e.g., calculator, simple login flow)
- Matplotlib practice: line plots, subplots, scatter, histograms, saving figures (e.g., `square_function.png`)
- Notes/examples include Azerbaijani-language strings in several cells

## Tech Stack

- Language: Python (notebook kernel metadata reports `3.14.0`)
- Notebooks: Jupyter (`.ipynb`)
- Libraries used in code cells:
  - NumPy (version not pinned)
  - Matplotlib (version not pinned)

No dependency lockfiles or environment files (e.g., `requirements.txt`, `pyproject.toml`) are present in the repository.

## Project Structure

```text
.
├── task1.ipynb
└── python learning journey
    ├── Python task 1.ipynb
    ├── Python task 2.ipynb
    ├── matplotlib_practice.ipynb
    ├── practice and experiment 1.ipynb
    └── test and small projects 1.ipynb
```

## Getting Started

### Prerequisites

- Python 3.x
- `pip`
- A notebook runner:
  - VS Code with the Jupyter extension, or
  - Jupyter Lab / Jupyter Notebook

### Installation

Create and activate a virtual environment, then install the dependencies used by the notebooks:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install jupyter ipykernel numpy matplotlib
```

### Configuration

This repository does not define any environment variables (no `.env` / `.env.example` present).

| Variable | Required | Default | Description |
|---------:|:--------:|:-------:|------------|
| (none)   |    —     |    —    | — |

### Run

Option A — Jupyter Lab:

```bash
jupyter lab
```

Option B — Classic Notebook:

```bash
jupyter notebook
```

Option C — VS Code:

1. Open any `.ipynb` file.
2. Select a Python interpreter / kernel.
3. Run cells interactively.

## Usage

Open and run the notebooks depending on what you want to practice:

- `task1.ipynb`: basic Python exercises (variables, arithmetic, strings)
- `python learning journey/Python task 1.ipynb`: similar fundamentals practice
- `python learning journey/Python task 2.ipynb`: collections + list/set practice and small logic tasks
- `python learning journey/matplotlib_practice.ipynb`: plotting examples with NumPy/Matplotlib (including subplots, scatter, histograms, saving figures)
- `python learning journey/test and small projects 1.ipynb`: loop/conditional exercises and small “project-like” snippets (calculator/login examples)
- `python learning journey/practice and experiment 1.ipynb`: assorted experimentation and practice with Python lists and control flow

### Examples

Start Jupyter Lab and open the plotting notebook:

```bash
jupyter lab
```

Then open `python learning journey/matplotlib_practice.ipynb` and run cells top-to-bottom (or selectively).

## Testing

No automated test suite is included (no `pytest`, `unittest`, CI config, or test runner scripts found).

## Deployment

No deployment configuration is included (no Docker files, hosting config, or CI/CD workflows found).

## Troubleshooting

- Kernel not found / VS Code can’t run cells:
  - Ensure you installed `ipykernel` and selected the correct interpreter/kernel in your notebook UI.
- `ModuleNotFoundError: No module named 'numpy'` / `matplotlib`:
  - Install dependencies in your active environment: `pip install numpy matplotlib`.
- Some cells may be incomplete or contain syntax/logic mistakes:
  - This repo is a learning workspace; run cells one-by-one and treat errors as part of the exercises (fix and re-run).
- Cells using `input()` will block execution until you provide input in the notebook UI.

## Contributing

Lightweight contributions are welcome:

- Keep changes scoped (one notebook/topic per PR where possible)
- Prefer clear notebook cell outputs and minimal noise in diffs
- If you add new dependencies, consider adding a `requirements.txt` to make setup reproducible

## License

No license file found.
