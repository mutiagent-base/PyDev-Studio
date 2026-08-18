# PyDev-Studio
A modern, high-performance web-based Python development environment, function runner, and test suite manager with AI-assisted code generation, GitHub cloud sync, and color-coded logging diagnostics.

---

## ⚡ Quick Start & Installation

### Option 1: Automated Installer (macOS & Linux)
```bash
chmod +x install.sh
./install.sh
```

### Option 2: Windows Installer
Double-click `install.bat` or run:
```cmd
install.bat
```

### Option 3: Manual Installation
```bash
# 1. Install dependencies
npm install

# 2. Run in development mode
npm run dev

# 3. Or build and run for production
npm run build
npm start
```
Then visit **http://localhost:3000** in your browser.

---

## ✨ Features

- **Distraction-Free Maximize Mode**: Toggle full-screen editor overlay (`Esc` to exit) with line statistics.
- **Color-Coded Logging in ResultsPanel**: Real-time parsing of `DEBUG`, `INFO`, `WARNING`, `ERROR`, `CRITICAL`, and Python exception tracebacks with multi-level filtering and search.
- **Performance Diagnostics**: Microsecond-accurate script execution benchmarks and peak memory estimation.
- **Debounced Auto-Save**: Real-time background synchronization of code snippets with persistent localStorage fallback.
- **GitHub Sync**: Push and pull snippet collections to personal repositories with OAuth authentication or Personal Access Token.
- **AI Assist & Code Suggestions**: Intelligent code optimization, unit test generation, and bug fixing.
- **Python Package Management & Tools**: Live pip package viewer and terminal execution runner.
