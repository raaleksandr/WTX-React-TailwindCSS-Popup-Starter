# Minimalist Chrome/Firefox Extension Boilerplate with WXT + React + TypeScript + TailwindCSS

This repository provides a minimal, ready-to-use boilerplate for building browser extensions using <a href="https://github.com/wxt-dev/wxt">WXT</a>, React, TypeScript, and TailwindCSS.

It is based on the official <a href="https://github.com/wxt-dev/examples">WTX examples</a>.

## Installation

Clone the repository and install dependencies:

```sh
pnpm i
```

## Development

Start the dev server and begin hacking:

```sh
pnpm dev
```

Alternatively, you can load the extension in Chrome for testing:

- Open chrome://extensions/
- Enable Developer mode
- Click Load unpacked
- Select the generated .output/ folder

## Production Build

When you’re ready to publish:

```sh
pnpm build
```

## Troubleshooting

Tested with Node.js v22.17.0
