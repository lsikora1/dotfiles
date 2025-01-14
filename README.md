# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Install stow

### Stow

```
apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone https://github.com/lsikora1/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks, i.e

```
$ stow git
```