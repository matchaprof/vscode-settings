# My VSCode Settings

Find my settings for VSCode below!

## How it looks

![vscode-screenshot](vscode-ss.jpg)

# Font and Cursor

Search for **"Font"** in VSCode settings and change the following:
- Font Family: `"Monaspace Argon Var', monospace"` (<a href="https://monaspace.githubnext.com/#code-ligatures" target="_blank">Download from GitHub</a>)
- Font Fize: `16`

Search for **"Cursor"** in VSCode settings and change the following:
- Cursor Style: `Line`
- Cursor Blinking: `Phase`
- Cursor Width: `3`
- Cursor Smooth Caret Animation: `on`


# Extensions

### Formatting Help
Check my `settings.json` for compatibility using multiple formatters.
- <a href="https://github.com/prettier/prettier-vscode" target="_blank">Prettier - Code formatter</a> <br>Formats code by enforcing a consistent style by parsing your code and re-printing it with its own rules (Ctrl + S).

- <a href="https://github.com/mike7515/code-beautifier" target="_blank">Beautify</a> <br>Formats CSS code nicely after saving (Ctrl + S).

- <a href="https://github.com/xabikos/vscode-javascript" target="_blank">JavaScript (ES6) code snippets</a> <br>Code snippets for JavaScript in ES6 syntax (supports both JavaScript and TypeScript).

- <a href="https://github.com/solnurkarim/HTML-to-CSS-autocompletion" target="_blank">HTML To CSS Autocompletion</a> <br>Provides completion suggestions for classes and ids from markup documents to stylesheets.

- <a href="https://github.com/Cardinal90/multi-cursor-case-preserve" target="_blank">Multiple cursor case preserve</a> <br>Preserves case of selection when editing multiple cursors.

### Visual Styling

- <a href="https://github.com/oderwat/vscode-indent-rainbow" target="_blank">indent-rainbow</a> <br>Makes indentation easier to read (pairs nicely with `"editor.guides.bracketPairs": "active",` in ![settings.json](settings.json)).

- <a href="https://github.com/aaron-bond/better-comments" target="_blank">Better Comments</a> <br>This extension will help you create more human-friendly comments in your code. <br>Alerts, 
Queries, TODOs, Highlights, commented out code can also be styled to make it clear the code shouldn't be there, and more!

- <a href="https://github.com/johnpapa/vscode-peacock" target="_blank">Peacock</a> <br>Subtly change the color of your workspace. Ideal when you have multiple VS Code instances.

- <a href="https://github.com/enyancc/vscode-ext-color-highlight" target="_blank">Color Highlight</a> <br>Styles CSS/Web colors found in your document.

- <a href="https://github.com/antiantisepticeye/vscode-color-picker" target="_blank">vscode-color-picker</a> <br>A simple color picker for vscode that lets you use the default css color picker in other documents.

- <a href="https://github.com/streetsidesoftware/vscode-spell-checker" target="_blank">Code Spell Checker</a> <br>Spell checker to help catch common spelling errors in code.

### Debugging and Troubleshooting

- <a href="https://github.com/alefragnani/vscode-bookmarks" target="_blank">Bookmarks</a> <br>Mark lines and jump to them. Move between important positions easily and quickly.

- <a href="https://github.com/usernamehw/vscode-error-lens" target="_blank">Error Lens</a> <br>Improve highlighting of errors, warnings and other language diagnostics.

- <a href="https://github.com/MicrosoftDocs/intellicode" target="_blank">Intellicode</a> <br>Allows you to see real-world examples of how other developers have used a given function via Github.

- <a href="https://github.com/kufii/CodeSnap" target="_blank">Codesnap</a> <br>Quickly take screenshots of snippets of code.

### Testing and Preview

- <a href="https://github.com/ritwickdey/vscode-live-server" target="_blank">Live Server</a> <br>Launch a development local Server with live reload feature for static & dynamic pages.

- <a href="https://github.com/microsoft/vscode-livepreview" target="_blank">Live Preview</a> <br>An extension that hosts a local server for you to preview your web projects on! (Updates preview without saving file).

## Appearance

### Transparency/Glassy look
- <a href="https://github.com/hikarin522/GlassIt-VSC" target="_blank">Glassit-VSC</a> <br>Able to set the alpha/transparency of the window. <br><b>Increase</b> transparency with Ctrl+Alt+Z <br><b>Decrease</b> transparency with Ctrl+Alt+C

### Icons
- <a href="https://github.com/vscode-icons/vscode-icons" target="_blank">VSCode Icons</a> <br>Icons for Visual Studio Code (files icons).

### Themes
- <a href="https://github.com/ayu-theme/vscode-ayu" target="_blank">Ayu Theme</a>
- <a href="https://github.com/akamud/vscode-theme-onedark" target="_blank">Atom One Dark Theme</a>
- <a href="https://github.com/guilhermerodz/omni-owl" target="_blank">Omni Owl Theme</a>
- <a href="https://github.com/ahmadawais/shades-of-purple-vscode" target="_blank">Shades of Purple Theme</a>

# settings.json

![Settings](settings.json)

```
{
  // Global settings
  "workbench.settings.applyToAllProfiles": [
    "editor.fontFamily",
    "editor.fontSize",
    "glassit.alpha"
  ],
  "liveServer.settings.donotShowInfoMsg": true,
  "cSpell.enabled": false,
  "editor.wordWrap": "on",
  "editor.linkedEditing": true,
  "editor.tabSize": 2,

  // Shows folder trees rather than compacting them inline
  "explorer.compactFolders": false,

  // Font Settings
  "editor.fontSize": 16,
  "editor.fontLigatures": "'calt', 'ss02', 'ss03', 'ss04', 'ss05', 'ss07', 'ss08', 'ss09', 'liga'",
  "editor.fontFamily": "'Monaspace Argon Var', monospace",

  // Cursor Settings
  "editor.cursorWidth": 3,
  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.multiCursorModifier": "ctrlCmd",

  // Appearance and Themes
  "workbench.colorTheme": "Ayu Dark",
  "workbench.iconTheme": "vscode-icons",
  "glassit.alpha": 230,
  "editor.guides.bracketPairs": "active",
  "vscode-color-picker.languages": [
    "bat",
    "c",
    "cpp",
    "csharp",
    "dockercompose",
    "dockerfile",
    "fsharp",
    "git-commit",
    "git-rebase",
    "go",
    "haml",
    "html",
    "java",
    "javascript",
    "javascriptreact",
    "json",
    "jsonc",
    "latex",
    "lua",
    "makefile",
    "markdown",
    "pascal",
    "perl",
    "php",
    "plaintext",
    "powershell",
    "python",
    "ruby",
    "rust",
    "scss",
    "sass",
    "shellscript",
    "sql",
    "svelte",
    "swift",
    "typescript",
    "typescriptreact",
    "vb",
    "vue",
    "vue-html",
    "xml",
    "yaml"
  ],
  "prettier.tabWidth": 2,

  // Formatter used globally in VSCode
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  // Formatter specifically for HTML
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },

  // Formatter specifically for CSS
  "[css]": {
    "editor.defaultFormatter": "michelemelluso.code-beautifier"
  },

  // Better Comments settings
  //! Look at this!
  //? Double check this!
  /// Does not belong!
  //ed Educational purposes only!
  //todo Work on this! #38D44C #FFBE3B
  //* Highlight this!
  "better-comments.multilineComments": true,
  "better-comments.highlightPlainText": true,
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#f2f2f2",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "#AC042E",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#71FBAA",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "/",
      "color": "#474747",
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "ed",
      "color": "#474747",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo",
      "color": "#181817",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "#F9FA19",
      "bold": true,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#f2f2f2",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "#3A31D8",
      "bold": false,
      "italic": false
    }
  ],

  // Peacock Settings
  "peacock.affectTitleBar": true,
  "peacock.affectStatusBar": false,
  "peacock.elementAdjustments": {
    "activityBar": "lighten",
    "statusBar": "none",
    "titleBar": "none"
  },
  // plan to edit these colors
  "peacock.favoriteColors": [
    {
      "name": "Stone",
      "value": "#f2f2f2"
    },
    {
      "name": "Angular Red",
      "value": "#dd0531"
    },
    {
      "name": "Azure Blue",
      "value": "#007fff"
    },
    {
      "name": "JavaScript Yellow",
      "value": "#f9e64f"
    },
    {
      "name": "Mandalorian Blue",
      "value": "#1857a4"
    },
    {
      "name": "Node Green",
      "value": "#215732"
    },
    {
      "name": "React Blue",
      "value": "#61dafb"
    },
    {
      "name": "Something Different",
      "value": "#832561"
    },
    {
      "name": "Svelte Orange",
      "value": "#ff3d00"
    },
    {
      "name": "Vue Green",
      "value": "#42b883"
    }
  ]
}
```

# Honorable Mentions

### Font
- Font Family: `"'Cascadia Code', monospace"` (<a href="https://github.com/microsoft/cascadia-code" target="_blank">Download from Microsoft</a>)
