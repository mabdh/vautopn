# vautopn

a shell function to fuzzy search an IPSec VPN by name and connect to it automatically.
inspired by [lazy-connect](https://github.com/thecasualcoder/lazy-connect)
modified to run in monterey

## Install

Install homebrew if not installed yet

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

If homebrew is already installed, run
```
brew tap mabdh/repo && brew install vautopn
```

## Usage

```
vautopn - Shell function to fuzzy search an IPSec VPN by name
               and connect to it automatically.

-i    - Initialize vautopn. Stores the TOTP secret and VPN list.
-r    - Refresh vpn list in ~/.config/vautopn .
-n    - Do not fill the password automatically. Instead copy the password to clipboard.
-h    - Show this help.
```
