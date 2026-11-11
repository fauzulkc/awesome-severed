# Awesome Severed [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools for keeping work and personal AI apart: separate accounts, separate memory, separate everything.

Your employer's Claude, your client's Claude and your own Claude shouldn't share a login, a memory or a chat history. This list collects tools and techniques that keep them severed, so you can run them side by side without signing out, mixing context or leaking one into the other.

## Contents

- [Claude](#claude)
- [Built-in mechanisms](#built-in-mechanisms)
- [Contributing](#contributing)

## Claude

- [Claude Severance](https://github.com/fauzulkc/claude-severance) - Run your personal and org Claude accounts at the same time: a separate Claude Desktop window and Claude Code command per account, each with its own login, memory, settings and history. Picks the account by folder, shows a signed-in badge in Claude Code's status line, and installs without administrator rights. Windows; macOS and Linux in preview.

## Built-in mechanisms

The pieces the tools above build on, if you want to do it by hand.

- [`CLAUDE_CONFIG_DIR`](https://code.claude.com/docs/en/settings) - Environment variable that points Claude Code at a different folder for its settings, session history and plugins, so each folder is its own setup.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.
