**Config files for [`stow`](https://www.gnu.org/software/stow/), k symlink farm manager.**

    ├── .stow-global-ignore     Ignore files based on naming scheme
    └── .stowrc                 Set $HOME as default target dir

### Install notes

**Important:** This should be the first package you install as it is responsible for filtering *README*, subpackages files trees when you stow a package.

Edit your `$HOME` full path in [.stowrc](.stowrc)

#### Install GNU Stow

```shell
# Debian / Ubuntu
sudo apt install stow

# macOS - assumes Homebrew << https://brew.sh/ >> is installed
brew install stow
```