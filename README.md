<img align="right" src="data/icon.png" height="146" width="151">

# JooxDownloader
Shell Scripts bodged together to download music from Joox

## Requirements
* Anything that can execute shell scripts
* Support for these commands : 
```
mkdir  cp     rm     echo
sleep  sed    tr     grep
xargs  wget   cd     cat
sort   mv     find   rename 
```
* `rename` must be a perl command (the one that supports regex)
* and pipeline support (just `|` and `&&` is enough)

TL;DR A Linux OS or something similar (such as Win10's Bash shell)
## "Installation"
1. Download files 
![Release](https://img.shields.io/github/release/nutchapolsal/jooxdownloader.svg) or Clone the files from Git Bash
2. Run firsttime.sh to make directories and "create" input file
## How to Use
Put link from Joox into input.txt then run boot.sh to download songs

It will download 2 versions for each link, an m4a and mp3

In test runs, I found that some link will not provide mp3 download so it's for safety

Also, the m4a will have lower quality(maybe) but Joox will always give the link while mp3 has better quality but sometime Joox will just not give the link
### Badges
i like em

![OS](https://img.shields.io/badge/os-linux-blue.svg)
![Lang](https://img.shields.io/badge/lang-sh-orange.svg)
[![Discord](https://img.shields.io/discord/291247686777307137.svg?label=discord&colorB=7289DA)](https://discord.gg/FhxPSCg)

[![Issues](https://img.shields.io/github/issues/NutchapolSal/JooxDownloader.svg)](https://github.com/NutchapolSal/JooxDownloader/issues)
[![Forks](https://img.shields.io/github/forks/NutchapolSal/JooxDownloader.svg)](https://github.com/NutchapolSal/JooxDownloader/network)
[![Stars](https://img.shields.io/github/stars/NutchapolSal/JooxDownloader.svg)](https://github.com/NutchapolSal/JooxDownloader/stargazers)
[![License](https://img.shields.io/github/license/NutchapolSal/JooxDownloader.svg)](https://github.com/NutchapolSal/JooxDownloader/blob/master/LICENSE)

![Release](https://img.shields.io/github/release/nutchapolsal/jooxdownloader.svg)
![All Releases](https://img.shields.io/github/downloads/NutchapolSal/JooxDownloader/total.svg)
![Last commit](https://img.shields.io/github/last-commit/nutchapolsal/jooxdownloader.svg)
![Commits (since latest release)](https://img.shields.io/github/commits-since/NutchapolSal/JooxDownloader/latest.svg)

![Open Issues](https://img.shields.io/github/issues-raw/nutchapolsal/jooxdownloader.svg)
![Closed Issues](https://img.shields.io/github/issues-closed-raw/nutchapolsal/jooxdownloader.svg)
![Open Pull Requests](https://img.shields.io/github/issues-pr-raw/nutchapolsal/jooxdownloader.svg)
![Closed Pull Requests](https://img.shields.io/github/issues-pr-closed-raw/nutchapolsal/jooxdownloader.svg)

![GitHub contributors](https://img.shields.io/github/contributors/nutchapolsal/jooxdownloader.svg)
![Search Hit Counter](https://img.shields.io/github/search/nutchapolsal/jooxdownloader/goto.svg)
![Code Size](https://img.shields.io/github/languages/code-size/nutchapolsal/jooxdownloader.svg)
![Repo Size](https://img.shields.io/github/repo-size/nutchapolsal/jooxdownloader.svg)

#### Note
This program cannot be used to pirate VIP Joox songs
but why even bother, 1 minute on google will probably find it anyways
