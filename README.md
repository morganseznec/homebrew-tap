# morganseznec/homebrew-tap

Homebrew casks for my tools.

## hop-cli (installs the `hop` command)

Reach any EC2 instance in any of your AWS accounts and regions through Session Manager.

```bash
brew install --cask morganseznec/tap/hop-cli
```

Source, issues and docs: [morganseznec/hop](https://github.com/morganseznec/hop).

The casks in this repository are written by each release of the tool, through
GoReleaser. Do not edit them by hand: changes would be overwritten by the next release.

The cask is named `hop-cli` because Homebrew's main repository already has an
unrelated `hop` cask. It installs the `hop` command. Casks installed earlier as
`morganseznec/tap/hop` are migrated by `cask_renames.json` on the next `brew upgrade`.
