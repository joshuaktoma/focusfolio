# focusfolio

Chrome extension that tracks reading time per tab

## What it does

- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- No remote calls, everything stays local
- Manifest V3, service worker based

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## License

MIT. Do whatever you want.
