# brew-file
🖥 Brewfile for setting up new Apple computer

My personal suite of tools, or what's available on Homebrew, in one `Brewfile`.

## Usage

To install Homebrew and brew-file:

```
$ curl -fsSL https://raw.github.com/rcmdnk/homebrew-file/install/install.sh |sh
```

To use this Brewfile via `brew bundle`:

```sh
$ brew bundle
```

To use this Brewfile via `brew-file`, which has more capabilties than bundle:

```sh
$ brew install rcmdnk/file/brew-file
$ brew file init                    
Do you want to set a repository (y)? ((n) for local Brewfile). [y/n]: y
Set repository, "non" for local Brewfile,
<user>/<repo> for github repository,
or full path for the repository: frankstallone/brew-file
```