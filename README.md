# dotfiles

My personal dotfiles, managed with [chezmoi](https://chezmoi.io).

## Install

On a fresh machine:

```sh
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply mephs
```

## Layout

```
.
├── .chezmoi.toml.tmpl      # chezmoi config template
├── .chezmoiignore          # files not to apply to $HOME
├── .commit_message.tmpl    # auto-commit message format
├── dot_config/             # → ~/.config/
```

## License

MIT

