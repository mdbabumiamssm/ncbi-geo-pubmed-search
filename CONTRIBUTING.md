# Contributing to ncbi-geo-pubmed-search

Thank you for your interest in contributing! We welcome contributions from everyone.

## How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Run tests (`pytest tests/`)
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/ncbi-geo-pubmed-search.git
cd ncbi-geo-pubmed-search

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install in development mode
pip install -e .
pip install -r requirements-dev.txt
```

## Running Tests

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov=ncbi_geo_pubmed

# Run specific test
pytest tests/test_basic.py::TestNCBISearcher
```

## Code Style

We use Black for code formatting and flake8 for linting:

```bash
# Format code
black ncbi_geo_pubmed tests

# Check linting
flake8 ncbi_geo_pubmed tests
```

## Reporting Issues

Please use the GitHub issue tracker to report bugs or request features.
