# Repository structure

This repository should only contain
* Submodules with each submodule being a single git command
* Gitconfig files named `gitconfig.<suffix>`
* This `README.md`

## Gitconfigs

Include gitconfigs with e.g. the corresponding lines in your `.gitconfig`:
```
[include]
    path = <path>/gitconfig.<suffix>
```