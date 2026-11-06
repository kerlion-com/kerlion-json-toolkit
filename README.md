# KERLION JSON Toolkit

A privacy-first JSON workspace for developers that runs entirely in the browser.

**Latest release:** [v1.0.0](https://github.com/kerlion-com/kerlion-json-toolkit/releases/tag/v1.0.0)

## Arabic Usage Guide

Prefer instructions in Arabic? Read the [Arabic project and usage guide](https://www.kerlionvip.com/2026/11/kerlion-json-toolkit.html) for an explanation of the toolkit and how to use its features.

## Features

- JSON Formatter and Minifier
- JSON Validator
- Conservative JSON Repair
- JSON Tree Viewer
- JSON Diff
- Simple JSONPath Tester
- JSON Statistics
- Copy and download results
- Drag & Drop JSON files
- Arabic RTL and English interface
- Light and dark themes
- Keyboard shortcuts
- No backend, API, database, or external JavaScript libraries

## Privacy

All JSON processing is performed locally in the browser. JSON content is not sent to a remote server by this application.

## Run locally

No build step is required.

1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. Paste JSON or load a `.json` file.
4. Use the available tools.

## Keyboard shortcuts

- `Ctrl/Cmd + Enter` — Format JSON
- `Ctrl/Cmd + K` — Clear editor

## JSONPath support

This release supports:

- Root selector: `$`
- Dot properties: `$.user.name`
- Array indexes: `$.users[0]`
- Quoted bracket properties: `$["user-name"]`
- Wildcards: `$.users[*]` and `$.users.*`

Recursive descent (`..`) and advanced JSONPath expressions are not included in v1.0.0.

## Project structure

```text
kerlion-json-toolkit/
├── index.html
├── styles.css
├── app.js
├── README.md
├── LICENSE
└── assets/
    └── favicon.svg
```

## License

MIT License. See [LICENSE](LICENSE).

## KERLION

Official website: https://www.kerlionvip.com

GitHub: https://github.com/kerlion-com
