# Config-vsCode

{
  //editor de texto
  "editor.rulers": [
    80,
    120
  ],
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  "editor.fontLigatures": true,
  //arquivos
  "terminal.integrated.fontFamily": "JetBrains Mono",
  "explorer.compactFolders": false,
  "editor.minimap.enabled": false,
  "editor.formatOnSave": true,
  "editor.wordWrap": "on",
  "files.autoSave": "afterDelay",
  "window.menuBarVisibility": "compact",
  "window.commandCenter": false,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "editor.formatOnPaste": true,
  "workbench.startupEditor": "none",
  //terminal
  "terminal.integrated.profiles.windows": {
    "PowerShell": {
      "source": "PowerShell",
      "icon": "terminal-powershell"
    },
    "Command Prompt": {
      "path": [
        "${env:windir}\\Sysnative\\cmd.exe",
        "${env:windir}\\System32\\cmd.exe"
      ],
      "args": [],
      "icon": "terminal-cmd"
    },
    "Git Bash": {
      "source": "Git Bash"
    }
  },
  //VSCode Animations
  "workbench.settings.applyToAllProfiles": [
    "workbench.colorCustomizations"
  ],
  "animations.Install-Method": "Apc Customize UI++",
  "apc.imports": [
    "file:///c:/Users/fabia/.vscode/extensions/brandonkirbyson.vscode-animations-2.0.4/dist/updateHandler.js"
  ],
  "animations.Enabled": false,
  "editor.cursorSmoothCaretAnimation": "explicit",
  // UI customizations
  "workbench.list.typeNavigationMode": "trigger",
  "window.titleBarStyle": "custom",
  "workbench.layoutControl.enabled": false,
  "workbench.editor.editorActionsLocation": "hidden",
  "editor.stickyScroll.scrollWithEditor": false,
  "workbench.tree.enableStickyScroll": false,
  "workbench.colorCustomizations": {
    "editorCursor.foreground": "#ff00dd",
    "editorCursor.background": "#ffffff",
    "editor.lineHighlightBackground": "#1073cf4c",
    "editorHoverWidget.border": "#1073cf",
    "editorSuggestWidget.border": "#1073cf"
  },
}
