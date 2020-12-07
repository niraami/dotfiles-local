# Dotfiles (local)
This repo includes some device-specific dotfiles that are impossible (or ugly) to generalize in my main [dotfiles](https://github.com/niraami/dotfiles "github.com/niraami/dotfiles") for my various devices (be it a notebook, desktop or a server). Most of these files are designed to work in conjunction with my main dotfiles - or even override them.

## Structure
Each device configuration (profile) is fully contained in its own branch, while the master branch mostly works as a bare-minimum template to create a new profile.

## Installation
After cloning, just run the `install` script. It's quite possible that it may ask for sudo permissions if there are any packages being installed, or links created outside of the `home` path.
