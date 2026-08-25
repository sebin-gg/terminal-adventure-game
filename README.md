# 🎮 Terminal Adventure Game

[![Python 3](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Security: Gitleaks](https://img.shields.io/badge/Security-Gitleaks-green.svg)](https://github.com/gitleaks/gitleaks)

An interactive text-based adventure game written in Python featuring branching story pathways, multiple locations, inventory management, dynamic encounters, and progress saving.

---

## 🌟 Features

- **Branching Storylines:** Multiple endings based on player choices and decisions.
- **Inventory & Items System:** Collect, examine, and use key items to unlock secrets.
- **Save & Load:** Built-in persistence to save game state and resume anytime.
- **Zero External Dependencies:** Built with pure Python standard library for instant execution on any platform.

---

## 🚀 Quickstart

### 1. Clone the Repository
```bash
git clone https://github.com/sebin-gg/terminal-adventure-game.git
cd terminal-adventure-game
```

### 2. Start the Game
```bash
python adventure_game.py
```

Follow the on-screen prompts to explore different rooms, make choices, and uncover the mystery.

## 🔒 Security

This repository uses [gitleaks](https://github.com/gitleaks/gitleaks) for automatic secret scanning on every commit.

### Pre-commit Hook

A pre-commit hook is configured to scan for secrets before each commit. This helps prevent accidentally committing sensitive information like:
- API keys
- Passwords
- Tokens
- Private keys

### Setup

To enable the pre-commit hook locally:

```bash
# Install pre-commit
pip install pre-commit

# Install hooks
pre-commit install
```

### Bypass (Emergency Only)

In case of emergency, you can bypass the hook:

```bash
git commit --no-verify -m "emergency commit"
```

> ⚠️ Only use `--no-verify` in emergency situations. Regular commits should always be scanned.

