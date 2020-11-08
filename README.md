# pre-commit: oelint-adv mirror

Mirror of [oelint-adv](https://github.com/priv-kweihmann/oelint-adv) package for [pre-commit](https://pre-commit.com/).

## Usage

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/skycaptain/pre-commit-oelint-adv
  rev: ''  # Use the sha / tag you want to point at
  hooks:
    - id: oelint-adv
```
