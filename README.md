# Dotfiles

This dotfiles utilize [chezmoi][1]. Be sure to [get it installed][2], then [read the basic usage][3]. Simple as that.

I haven't found the written docs, but as I observed it, it mostly depends on `git` as how it initialize a blank chezmoi or remote one. Be sure to get [Git][4] installed on your machine.

## Quick Run

### 1. Init
On Unix-like:
```sh
$ chezmoi init --apply gphg
```

On Windows (cmd or powershell):
```bat
> chezmoi init --apply gphg
```

### 2. Sync
1. pull remote:
```
$ chezmoi update
```

2. apply changes:
```
$ chezmoi apply
```

More operations, read the [docs page][5].

## What's inside?
TODO: list summary of contents.

## What's next?
This dotfiles won't install essential packages for you. You have to get it intalled yourself via proper package manager (or your own build). Check the [list of essentials](essentials.txt).

A package usually initialize its own config file(s) and might conflicts with this (easily can be fixed). Be sure to get this dotfiles initialized then install the package.

[1]: https://www.chezmoi.io/
[2]: https://www.chezmoi.io/docs/install/
[3]: https://www.chezmoi.io/docs/quick-start/
[4]: https://git-scm.com/
[5]: https://www.chezmoi.io/docs/how-to/
