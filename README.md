# git wipe-branch

Wipe, eradicate, destroy, kill, abolish a git branch. Seriously.

- Local branch
- Local remote tracking branch
- Remote branch with `--remote` flag

Licensed under the **MIT** license, see LICENSE for more information.


## Installation

Add as a bundle through [Antigen](https://github.com/zsh-users/antigen):

    antigen bundle timkurvers/git-wipe-branch


## Usage

    git wipe-branch feature/foobar

To also wipe the remote branch, use the `--remote` flag:

    git wipe-branch feature/foobar --remote
