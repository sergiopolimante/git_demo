# Git Demo — DevOps

A demo Python project showcasing unit testing with **pytest** and CI via **GitHub Actions**.

## Project Structure

```
git_demo/
├── src/
│   ├── calculator.py      # Arithmetic operations
│   └── string_utils.py    # String helper functions
├── tests/
│   ├── test_calculator.py  # Calculator unit tests
│   └── test_string_utils.py# String utils unit tests
├── .github/workflows/
│   └── test.yml            # CI workflow (runs on PRs)
├── requirements.txt
└── README.md
```

## Getting Started

```bash
pip install -r requirements.txt
```

## Running Tests Locally

```bash
pytest tests/ -v
```

## CI / CD

A GitHub Actions workflow (`.github/workflows/test.yml`) runs the full test suite on every pull request, across Python 3.10, 3.11, and 3.12.
