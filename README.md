# WorkTreeBuddy

Streamline your Git worktree workflow with quick access from your macOS menu bar.

![macOS 15+](https://img.shields.io/badge/macOS-15%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Latest Release](https://img.shields.io/github/v/release/oreillymedia/worktreebuddy)

## Overview

WorkTreeBuddy is a lightweight macOS menu bar application that makes working with Git worktrees effortless. Access all your worktrees, check their status, and open them in your favorite development tools - all from a convenient menu bar icon.

## ✨ Features

- **🌳 Menu Bar Access** - Quick access to all worktrees via the tree icon in your menu bar
- **📊 Status Indicators** - Visual indicators show worktree states at a glance:
  - 🟠 Orange dot: Uncommitted changes
  - 🔴 Red dot: Inaccessible worktree
  - No dot: Clean worktree
- **🚀 Quick Actions** - Right-click any worktree for instant access:
  - Open in your IDE
  - Open in Git client
  - Open in Terminal
  - Delete worktree (with safety checks)
- **🔄 Auto-Refresh** - Automatically updates when worktrees change
- **⚙️ Customizable** - Configure your preferred IDE, Git client, and terminal applications
- **🔐 Secure** - Sandboxed application with minimal permissions
- **📦 Auto-Updates** - Built-in automatic updates via Sparkle framework

## 📋 Requirements

- macOS 15.0 (Sequoia) or later
- Git installed and accessible from Terminal

## 📥 Installation

### Download

1. Download the latest release from the [Releases](https://github.com/oreillymedia/worktreebuddy/releases/latest) page
2. Open the downloaded DMG file
3. Drag WorkTreeBuddy to your Applications folder
4. Launch WorkTreeBuddy from Applications
5. Look for the 🌳 tree icon in your menu bar

### First Launch

When you first launch WorkTreeBuddy:

1. Click the tree icon in the menu bar
2. You'll be prompted to select your Git repository
3. The app will display all worktrees in that repository
4. When opening a worktree for the first time, select your preferred applications

## 🎯 Usage

### Basic Operations

- **View Worktrees**: Click the tree icon to see all worktrees
- **Check Status**: Look for colored dots indicating worktree status
- **Open Worktree**: Click a worktree name to see available actions
- **Quick Switch**: Use keyboard shortcuts (coming soon)

### Preferences

Access preferences from the menu to:
- Change your Git repository
- Set default applications for opening worktrees
- Configure update settings

### Worktree Management

WorkTreeBuddy helps you:
- Quickly identify which worktrees have uncommitted changes
- Access any worktree in your preferred development environment
- Keep track of multiple feature branches simultaneously
- Clean up unused worktrees safely

## 🔄 Updates

WorkTreeBuddy includes automatic update checking. When an update is available:
- You'll see a notification in the menu
- Click "Check for Updates..." to manually check
- Updates are downloaded and installed automatically

## 🐛 Troubleshooting

### Tree icon not appearing
- Check if WorkTreeBuddy is running in Activity Monitor
- Try launching from Applications folder again
- Restart your Mac if the issue persists

### Repository not found
- Ensure your repository contains a `.git` folder
- Check that you have read permissions for the repository
- Try selecting the repository folder again in Preferences

### Worktrees not updating
- Click the tree icon to manually refresh
- Check if the repository path is still valid
- Verify Git is working correctly in Terminal

## 🤝 Support

- **Issues**: Report bugs or request features on our [Issues page](https://github.com/oreillymedia/worktreebuddy/issues)
- **Discussions**: Join the conversation in [Discussions](https://github.com/oreillymedia/worktreebuddy/discussions)

## 📄 License

WorkTreeBuddy is released under the MIT License. See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- Built with SwiftUI for macOS
- Uses [Sparkle](https://sparkle-project.org/) for automatic updates
- Icon designed with SF Symbols

---

Made with ❤️ for developers who love Git worktrees