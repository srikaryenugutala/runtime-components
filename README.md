# runtime-components

My personal configuration files for bash, zsh, vim, git, and gdb, so any new machine is set up in one command.

## Contents
- `.bashrc` shell settings, prompt with git branch, aliases
- `.zshrc` zsh and oh-my-zsh setup matching the bash aliases
- `.vimrc` line numbers, 2-space indentation, search settings
- `.gitconfig` default branch, editor, and git aliases
- `.gdbinit` history and pretty printing for gdb
- `install.sh` copies everything into place

## Install
    git clone git@github.com:srikaryenugutala/runtime-components.git
    cd runtime-components
    ./install.sh --dry-run   # preview
    ./install.sh             # install
