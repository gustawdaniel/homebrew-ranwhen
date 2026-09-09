# Homebrew Tap for ranwhen

Official Homebrew tap for [ranwhen](https://github.com/gustawdaniel/ranwhen) – terminal uptime and activity session visualizer written in Rust.

## Installation

```bash
brew tap gustawdaniel/ranwhen
brew install ranwhen
```

Or in a single command:
```bash
brew install gustawdaniel/ranwhen/ranwhen
```

## Features on macOS
- Native screen / backlit power tracking (CoreDuet).
- Automatically installs and configures background LaunchAgent daemon (`ranwhen --install-daemon`) to archive activity sessions into `~/.local/share/ranwhen/activity_sessions.log`.
