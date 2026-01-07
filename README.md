# Fluent Script Language Support

VS Code syntax highlighting for the FluentScript programming language. Files ending with `.fls` (or without the dot) are recognized automatically.

## Features
- TextMate grammar for FluentScript keywords, comments, strings, numbers, and core functions (see `syntaxes/fluent-script.tmLanguage.json`).
- Bracket matching, auto-closing pairs, and comment toggling via `language-configuration.json`.
- File associations for `.fls` and `fls` files so they open with FluentScript highlighting by default.

## Usage
1. Install the extension (from a packaged VSIX or the marketplace once published).
2. Open any `.fls` file to get FluentScript highlighting and editor language features.

## Notes
- The extension has no runtime dependencies and works fully offline once installed.
- Pull requests are welcome for additional language features (snippets, hover info, formatting, etc.).
