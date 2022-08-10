# MY-VSCODE-EXTENSION

## 介绍

这是我目前主要正在使用的vscode插件的安装脚本。因为vscode现在已经支持了使用code --install-extension命令在命令行安装插件，所以创建这个仓库编写一个安装插件的脚本方便我跨设备使用。同时也分享出来供大家使用或参考

## 主要内容

因为我的几台设备性能都不是很好，所以我vscode安装的插件不会太过累赘，都是刚刚好。主要的插件还是面向我前端方面的学习与开发，同时参杂了一些自我喜欢的一些个性化插件（如主题）和一些“必需品”（如c/c++、python支持插件）。但是一些需要登录账号的，并不是每个人都需要的插件我没有放进去（极少数，如live share、github codespaces等，如果我需要我也会独立安装）

主要包含的插件有：

- ms-ceintl.vscode-language-pack-zh-hans //简体中文语言包

- github.github-vscode-theme //github theme（主题插件）

- ritwickdey.liveserver //live server

- pkief.material-icon-theme //material-icon-theme（图标插件）

- techer.open-in-browser //open in browser

- hookyqr.minify //minify

- formulahendry.auto-close-tag //auto close tag

- ormulahendry.auto-rename-tag //auto rename tag

- mrcrowl.easy-less //easy less

- shd101wyy.markdown-preview-enhanced //markdown preview enhanced（个人感觉是比自带markdown预览更好用）

- ecmel.vscode-html-css //HTML CSS Support

- ms-vscode.cpptools //C/C++

- ms-python.python //Python

- w88975.code-translate //code translate（翻译插件）

## 使用方法

本仓库的文件数为

```
│  README.md
│
├─Linux&Mac
│      install.sh
│
└─Windows
        install.bat
```

请使用下面命令讲本仓库克隆到本地

```
git clone https://github.com/leaf2006/my-vscode-extension.git
```

Windows用户请打开Windows目录下的install.bat

如果你是Linux或者Mac用户请打开Linux&Mac下的install.sh

## Thanks