# Case Converter Toolkit — V2

A standalone browser-based case conversion utility built with HTML, Alpine.js, and Tailwind CSS.

## Features
- kebab-case, camelCase, PascalCase, snake_case, SCREAMING_SNAKE_CASE, and Title Case
- Bulk mode: convert each input line independently
- Copy individual outputs or all results
- Dark/light theme toggle with saved preference
- Advanced settings for diacritics, numbers, and special characters
- Keyboard shortcuts: Ctrl+Enter to focus results, Ctrl+Shift+C to copy kebab-case, Esc to clear
- No backend or database

## Run
Extract the ZIP and open `kebab-case-converter/index.html` in a modern browser. Tailwind CSS and Alpine.js are loaded from CDNs, so an internet connection is needed for those libraries.

## Notes
- All conversions run client-side.
- Clipboard access is subject to browser security restrictions; a fallback is included.
