# Brewfile

Paste that at a Terminal prompt.


Install Homebrew

``` ruby
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

brew-file tap and install
``` bash
brew install rcmdnk/file/brew-file
```

set repository
``` bash
brew file set_repo -r trkw/Brewfile
```

file install
``` bash
brew file install
```

Add .bashrc or .zshrc
```
if [ -f $(brew --prefix)/etc/brew-wrap ];then
  source $(brew --prefix)/etc/brew-wrap
fi
```

## Package installation
``` bash
brew file brew install [package name]
brew file brew cask install [package name]
```

## Package update
``` bash
brew file brew update
```
