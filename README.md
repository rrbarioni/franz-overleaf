# Overleaf for Franz

An unofficial [Overleaf](https://www.overleaf.com/) recipe (plugin) for [Franz](https://meetfranz.com/).

## Installing

### Windows

With git and PowerShell:

```sh
mkdir $env:APPDATA\Franz\recipes\dev\
git clone git@github.com:rrbarioni/franz-overleaf.git $env:APPDATA\Franz\recipes\dev\franz-overleaf
```

With Explorer:

1. Download the `franz-overleaf.zip` from github.  Extract it to its own folder (`franz-overleaf`).
2. Open `%appdata%/Roaming/Franz/recipes/dev/`. The `dev` folder may not exist, so go ahead and create it.
3. Copy the `franz-overleaf` folder into the plugins directory.
4. Reload Franz.

### Mac

```sh
mkdir ~/Library/Application\ Support/Franz/recipes/dev/
git clone git@github.com:rrbarioni/franz-overleaf.git ~/Library/Application\ Support/Franz/recipes/dev/franz-overleaf
```

### Linux

```sh
mkdir ~/.config/Franz/recipes/dev
git clone git@github.com:rrbarioni/franz-overleaf.git ~/.config/Franz/recipes/dev/franz-overleaf
```
