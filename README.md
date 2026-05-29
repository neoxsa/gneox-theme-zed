# Gneox Theme for Zed

A neon-green dark theme for the [Zed](https://zed.dev) editor.

## Features

- Dark UI with high contrast
- Neon green accents
- Custom syntax highlighting
- Tuned terminal ANSI palette

## Installation

### From Zed Extensions (once published)

1. Open **Zed**
2. Go to **Extensions**
3. Search for **Gneox**
4. Install and select it in the theme picker

### Local (dev extension)

1. Open **Zed**
2. Go to **Extensions**
3. Click **Install Dev Extension**
4. Select this folder (the one containing `extension.toml`)
5. Pick **Gneox** from the theme picker

## Project Structure

```text
.
├── extension.toml
├── LICENSE
├── README.md
└── themes
    └── gneox-theme-zed.json
```

## Metadata

- Extension ID: `gneox-theme`
- Name: `Gneox`
- Version: `0.1.0`

## Development

Theme values are defined in:

- `themes/gneox-theme-zed.json`

Schema used:

- `https://zed.dev/schema/themes/v0.2.0.json`

## Publishing to Zed Extensions

This theme is published via PR to:

- `zed-industries/extensions`

High-level process:

1. Push this repo to GitHub
2. Fork and clone `zed-industries/extensions`
3. Add this repo as a submodule under `extensions/gneox-theme`
4. Add/update the `gneox-theme` entry in top-level `extensions.toml`
5. Run `pnpm sort-extensions`
6. Open a PR

## License

MIT © neoxsa
