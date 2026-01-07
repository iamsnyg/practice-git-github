hello guys, My name is Sunny

## Code Quality Checks

This project includes multiple ways to ensure code quality:

### 🔄 Automatic Checks (Recommended)

- **Pre-commit Hooks**: Automatically checks and formats code before each commit
- **VS Code**: Install recommended extensions for real-time feedback

### 🧪 Manual Checks

Run these commands anytime:

```bash
npm run lint              # Check all files (HTML, CSS, JS)
npm run lint:html         # Check only HTML files
npm run lint:css          # Check only CSS files
npm run lint:js           # Check only JavaScript files
npm run format            # Auto-format all files with Prettier
npm run format:check      # Check if files are formatted correctly
```

### ⌨️ VS Code Tasks

Press `Ctrl+Shift+P` → `Tasks: Run Task` → Select a lint task

### 🛠️ Setup Instructions

1. Install dependencies: `npm install`
2. Install VS Code extensions (you'll be prompted automatically)
3. Start coding - quality checks run automatically!
