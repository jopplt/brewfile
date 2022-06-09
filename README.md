# brewfile
Brewfile (collection) for fast setups in Mac OS

### Usage:
```
wget https://raw.githubusercontent.com/jopplt/brewfile/main/.Brewfile -P ~/ && brew bundle --global
```

### Requirements:
* Xcode Command Line Tools: `xcode-select --install`
* [brew.sh](https://brew.sh/): `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`


### Suggestions:
* Increase key repeat speed (requires reboot):
  ```
  defaults write -g InitialKeyRepeat -int 10 # normal minimum is 15 (225 ms)
  defaults write -g KeyRepeat -int 1 # normal minimum is 2 (30 ms)
  ```
