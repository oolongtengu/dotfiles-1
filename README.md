# dotfiles

This repository consists of configuration for any tools I use within my [Arch Linux][arch] and [Emacs][] development environment. I use a *lot* of tools which culminate in a sort of Unix IDE, I use [stow][] to link all of the required configuration into my home directory.

## Installation

Firstly, clone this repository down to `~/dotfiles`, a few things assume it's kept there, sorry.

> This is what I use when setting up a new machine after installing [Arch][]. Don't just run this on a whim, this is essentially my custom built desktop environment, it's perfect for me but <del>could</del> *will* ruin your set up. Feel free to take what you want from here, but be careful about installing my entire set up over yours by mistake. Maybe try it in a VM as an experiment.

Presuming you're using Arch Linux, you can just run `make`. This will install everything listed in `packages.txt` (including [yaourt][]), link all of the configuration into your home directory then switch the default shell to [fish][].

```bash
# Pre-awesome Linux environment.

make

# Awesome Linux environment.
```

To perform a system wide update you can execute `yolo` from within a [fish][] shell. This includes system, npm, emacs and vim packages as well as system maintenance. I run this every day, nothing has broken yet, maybe I'm lucky, or maybe all those naysayers were basing their opinions of Linux on hearsay and gossip. How odd. It's certainly more stable than OSX or Windows, that's for sure.

## Author
Forked from and heavily influenced by
[Oliver Caldwell][site] / [@OliverCaldwell][twitter]

Tweaking to my needs and workflows.
## Unlicenced

Find the full [unlicense][] in the `UNLICENSE` file, but here's a snippet.

>This is free and unencumbered software released into the public domain.
>
>Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

Do what you want. Learn as much as you can. Unlicense more software.

[unlicense]: http://unlicense.org/
[site]: http://oli.me.uk/
[twitter]: https://twitter.com/OliverCaldwell
[arch]: https://www.archlinux.org/
[stow]: http://www.gnu.org/software/stow/
[yaourt]: https://aur.archlinux.org/packages/yaourt/
[aur]: https://aur.archlinux.org/
[compton]: https://wiki.archlinux.org/index.php/Compton
[fish]: http://fishshell.com/
[antergos]: https://antergos.com/
[vim]: http://www.vim.org/
[emacs]: https://www.gnu.org/software/emacs/
