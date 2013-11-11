grget
=====

Download the latest release binary of a GitHub project from command line.

grget is useful for automating scripts that always want the latest release binary of a project. I use it in my [dotfiles](https://github.com/neilgupta/dotfiles) to fetch the latest release of QuickLook plugins when setting up my Mac. It is a bash script that requires wget to run. It will only download files added through the [GitHub Releases](https://github.com/neilgupta/grget/releases) feature.

## Installation

Place grget somewhere on your computer and add it to your PATH. Make sure you have wget installed on your computer. The easiest way to install wget is using homebrew.

## Usage

  grget -d ~/Desktop tabule/sherlock

This will fetch the latest version of [Sherlock](https://github.com/Tabule/Sherlock) and place it on your Desktop. Try `grget -h` for more detailed usage instructions.