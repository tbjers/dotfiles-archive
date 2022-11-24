# My new-new dotfiles

Powered by chezmoi, love, and the 'claw.

## Bootstrap a new machine

The quickest way to get up and running:

```sh
BINDIR="${HOME}/.local/bin" TAG="latest" sh \
  -c "$(curl -fsLS get.chezmoi.io)" -- init --apply tbjers
```
