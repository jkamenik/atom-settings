# Atom Settings

Contains all my personal settings for the [Atom](http://atom.io) editor.

## Installation

```bash
$ cd ~
$ git clone git@github.com:<account>/atom-settings.git .atom
$ cd .atom
$ apm install --packages-file packages.list
```

Since these are my setting, I recommend that you fork the repo into your own account and `git clone` from your version instead of mine.

## Update Package List

Periodically when packages are updated the package list needs to be regenerated

```bash
$ cd ~/.atom
$ apm list --installed --bare | sort > packages.list
```

## External dependencies

### AG - This Silver Surfer

Faster and nicer then grep.

`brew install ag`

