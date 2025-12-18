# Check commit message
pre-commit hook to validate the git commit message

## How to use
Create `.pre-commit-config.yaml` with the following lines:
```
repos:
  - repo: https://github.com/verbicloud/check_commit_msg
    rev: v0.0.7
    hooks:
    - id: commit-msg-hook
```

and simply run `$ pre-commit install --hook-type commit-msg`

## Good to know
There is a second [pre-commit hook](https://github.com/verbicloud/prepare_commit_msg/) that prepares the commit message with instructions
