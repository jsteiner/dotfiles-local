# dotfiles

I use [thoughtbot/dotfiles] as the foundation of my dotfiles. These files are the
`.local` modifications that build on top of that foundation.

[thoughtbot/dotfiles]: https://github.com/thoughtbot/dotfiles

## Install

Clone thoughtbot's dotfiles:

    git clone git://github.com/thoughtbot/dotfiles.git

Then clone mine:

    git clone git://github.com/jsteiner/dotfiles.git ~/dotfiles-local

Then run `rcup` to link:

    env RCRC=$HOME/dotfiles/rcrc rcup

This will create symlinks for config files in your home directory from
thoughtbot's dotfiles and my local customizations.

You can safely run `rcup` multiple times to update:

    rcup

## What's in it

Everything in [thoughtbot's dotfiles].

[thoughtbot's dotfiles]: https://github.com/thoughtbot/dotfiles

zsh configuration:

* An improved prompt with Git status
* [zsh-syntax-highlighting] gives you instant feedback of valid commands before
  running them
* [zsh-history-substring-search] for quickly rerunning old commands
* [fasd] for quickly accessing directories

[zsh-syntax-highlighting]: https://github.com/zsh-users/zsh-syntax-highlighting
[zsh-history-substring-search]: https://github.com/zsh-users/zsh-history-substring-search
[fasd]: https://github.com/clvv/fasd

vim configuration:

Everything in my [vimrc.bundles.local].

[vimrc.bundles.local]: https://github.com/jsteiner/dotfiles-local/blob/master/vimrc.bundles.local
