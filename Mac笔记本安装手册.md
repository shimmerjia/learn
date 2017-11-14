## 安装Mac开发环境

### [XCode](https://developer.apple.com/xcode/)

Xcode是运行在操作系统Mac OS X上的集成开发工具（IDE）,

用于开发Mac OS X，iOS的应用程序, 虽然咱们不开发iOS软件，但是在我们的前端开发中很多的软件需要

集成在xcode 里的一些开发工具的支持, 来帮助我们编译代码(eg: node.js, homebrew)


### [Homebrew](https://brew.sh/)

homebrew是mac系统下的软件包管理工具, 咱们要用到node, vim, git等都可以用它来进行安装

        brew install git/vim/node


### [Iterm2](https://www.iterm2.com/)

这是一个命令行终端工具，替换掉Mac系统默认的Terminal, 这个工具我只能说当你用熟之后不要太方便


### [Node.js](https://nodejs.org/en/)

XCode和Homebrew安装好之后，就可以安装Node了，不要告诉我你不知道为什么要安装node

它是我们前端开发最底层的支撑, 装好Node之后才有npm, 有了npm才能用npm install 来安装

咱们的react, redu, mobx等各种JS包.

### [yadr](https://github.com/skwp/dotfiles)

安装了上面这些东西之后就定制咱们的NB+ZB编辑器了:  ___zsh + Tmux + vim + git___

        sh -c "`curl -fsSL https://raw.githubusercontent.com/skwp/dotfiles/master/install.sh`"

