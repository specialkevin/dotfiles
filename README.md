# My Person Dotfiles

This repo contains dotfile configuration I use across various person and work machines. Inspiration for this dotfiles structure, i.e. stow, and specific configurations came from a number of sites, blogs, friends and coworkers. 

## How to Use

1. Clone Down Repo to Your Home Directory
2. Install [gnu stow](https://www.gnu.org/software/stow/)
    `brew install stow` or `apt-get install stow`
3. Setup Specific Configuration
    `cd ~/dotfiles; stow git`

## How it works

[GNU Stow](https://www.gnu.org/software/stow/) when passed a top-level directory within this repo will create any necessary folders to complete a matching directory structure starting from the home directory. Then it creates a symlink in that path to the specific file in this repo. This setup allows me to select specific configurations I want depending on the environment, work vs personal, while having one repository and one workflow. 

## Contributing / Suggestions

Feedback on improvements to this configuration is welcome and I enjoy discuss specific tools and how I find them useful. Please keep in mind that in some cases these configuration are more personal preference than a specific right or wrong way of doing things.
