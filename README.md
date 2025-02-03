# PyQt6-stubs

stubs-only package for PyQt6.

The rationale for this package is to provide a small stubs-only package for PyQt6, for use on pre-commit.ci, where the size of the entire environment is limited.


```yaml
  - repo: https://github.com/pre-commit/mirrors-mypy
    rev: v1.14.1
    hooks:
      - id: mypy
        additional_dependencies:
          - git+https://github.com/tlambert03/PyQt6-stubs.git@v6.7.3
```
