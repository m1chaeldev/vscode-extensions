# My current extensions

```
code --install-extension AykutSarac.jsoncrack-vscode
code --install-extension brittanychiang.halcyon-vscode
code --install-extension Cardinal90.multi-cursor-case-preserve
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
code --install-extension dbaeumer.vscode-eslint
code --install-extension donjayamanne.githistory
code --install-extension dracula-theme.theme-dracula
code --install-extension eamodio.gitlens
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-rename-tag
code --install-extension hnw.vscode-auto-open-markdown-preview
code --install-extension meganrogge.template-string-converter
code --install-extension ms-azuretools.vscode-docker
code --install-extension sidthesloth.html5-boilerplate
code --install-extension styled-components.vscode-styled-components
code --install-extension withfig.fig
code --install-extension yoavbls.pretty-ts-errors
```

# Export installed extensions command

## Windows
code --list-extensions | % { "code --install-extension $_" }

## MacOS
code --list-extensions | xargs -L 1 echo code --install-extension
