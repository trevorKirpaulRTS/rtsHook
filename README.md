# Tools

## git-secrets

> Note: [Homebrew](https://brew.sh/) required for the following steps

`git-secrets` will add a 'pre-commit' git hook which searches for AWS keys in commits and commit messages. If any keys are present, the commit will be blocked

### Installation

1. `$ brew update`
2. `$ brew install git-secrets`
3. Add `git-secrets` to your PATH

> using zsh

```sh
# ~/.zshrc

path+=('git-secrets')
```


