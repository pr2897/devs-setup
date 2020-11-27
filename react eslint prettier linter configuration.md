# **React linter configuration** _eslint, prettier_

> **Step 1** : Install dependencies

```bash
    npm i -D eslint-config-prettier eslint-plugin-prettier prettier
```

> **Step 2** : Install Extentions

- **ESLint**
  dbaeumer.vscode-eslint
- **Prettier**

> **Step 3** : create a "**.eslintrc**" file and paste following code

```javascript
{
    "extends": [
        "react-app",
        "plugin:prettier/recommended"
    ]
}
```

> **Step 4**: paste following snippets in the setting.json file

```javascript

{
    "editor.formatOnSave": true,
    "[javascript]": {
        "editor.formatOnSave": false,
    },
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontFamily": "'Fira Code'",
    "editor.fontLigatures": true,
    "prettier.arrowParens": "avoid",
    "material-icon-theme.hidesExplorerArrows": true,
    "editor.fontWeight": "500",
    "editor.fontSize": 14,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
    },
    "eslint.alwaysShowStatus": true,
    "prettier.disableLanguages": [
        "js"
    ],
    "files.autoSave": "onFocusChange",
    "explorer.confirmDelete": false,
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.renameOnType": true,
    "window.zoomLevel": 0,
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "C_Cpp.updateChannel": "Insiders",
    "workbench.colorTheme": "Atom One Dark",
    "workbench.activityBar.visible": true,
    "C_Cpp.commentContinuationPatterns": [
        "/**"
    ],
    "C_Cpp.clang_format_fallbackStyle": "{ BasedOnStyle: Google, IndentWidth: 4, ColumnLimit: 0}",
    "javascript.updateImportsOnFileMove.enabled": "always"
}

```
