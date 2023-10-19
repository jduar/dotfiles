# Dotfiles

A depository for configs and scripts I use on some machines.

All files are currently managed with [GNU Stow](https://www.gnu.org/software/stow/).

## Usage

```sh
$ cd dotfiles
$ stow .
```

This will create all directories with the same file structure within the `$HOME` directory and deploy all files as symlinks.
