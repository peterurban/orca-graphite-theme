# Graphite for Orca

A soft, low-glare dark theme for [Orca](https://github.com/stablyai/orca), covering both the app UI and the terminal.

It contributes:

- **App theme** `Graphite` (dark) – surfaces, sidebars, tabs, chat, diffs, git decorations and editor syntax colours (`tokenColors`) drawn from the Graphite palette.
- **Terminal theme** `Graphite` – the full 16-colour ANSI palette plus cursor and selection colours.

## Palette

| Role | Colour |
| --- | --- |
| Background | `#1c1e22` |
| Foreground | `#d2d6dc` |
| Cursor | `#c4cedb` |
| Selection | `#2e333b` |

| | Black | Red | Green | Yellow | Blue | Magenta | Cyan | White |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Normal | `#15171a` | `#e58888` | `#a7c59f` | `#cec59d` | `#8db4d0` | `#baabcb` | `#a8c6d4` | `#b4b9c0` |
| Bright | `#7e8590` | `#f19f9f` | `#b9d5b1` | `#cfba97` | `#a5c6de` | `#ccbedd` | `#bcd6e2` | `#eceff3` |

The upstream scheme's selection foreground (`#5c5e62`, about 2:1 on the selection background) is intentionally omitted, so selected text keeps its own colour.

Graphite has no light variant; pick it for Orca's **Dark** slot.

## Use

After installing, open **Settings → Appearance** and choose **Graphite** as the dark app theme and as the terminal theme.

## Develop

```sh
orca plugin validate .
orca plugin dev watch .    # loads this folder into Orca and live-reloads on save; Ctrl-C unloads it
```

See the [Orca plugin authoring guide](https://github.com/stablyai/orca/blob/main/docs/reference/plugin-authoring.md).

## Credits

The Graphite colour scheme was created by [PoshPalette](https://github.com/livlign/posh-palette) and is distributed through [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes) (MIT). Copyright in the original scheme belongs to its author. This plugin adapts it for Orca.
