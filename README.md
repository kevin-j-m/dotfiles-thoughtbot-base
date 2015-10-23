kevin-j-m dotfiles
===============

This is based off of the dotfiles from [Dan Croaky](https://github.com/croaky/dotfiles).

I use [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles) and
kevin-j-m/dotfiles together using [the `*.local` convention][dot-local].

[dot-local]: http://robots.thoughtbot.com/manage-team-and-personal-dotfiles-together-with-rcm

Requirements
------------

Set zsh as my login shell.

    chsh -s /bin/zsh

Install [rcm](https://github.com/mike-burns/rcm).

    brew tap thoughtbot/formulae
    brew install rcm

Install
-------

Clone onto my laptop:

    git clone git://github.com/kevin-j-m/dotfiles.git

Install:

    env RCRC=$HOME/kevin-j-m/dotfiles/rcrc rcup

This will create symlinks for config files in my home directory.

I can safely run `rcup` multiple times to update.
