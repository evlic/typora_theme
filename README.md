# evlic@Typora theme

## fork-list
- [Notion Theme](https://github.com/adrian-fuertes/typora-notion-theme)
    - 修改 dark* 模式的光标颜色，[参考博客](https://www.jianshu.com/p/b4929d09e275)

- [Themeable](https://github.com/jhildenbiddle/typora-themeable)
  - 

## install tutorial

```shell
###
# macOS 
###

cd ~/Library/Application\ Support/abnerworks.Typora

rm -rf themes

git clone https://lab.evlic.cn/evlic/typora-theme.git themes

killall Typora

open -a Typora

```

enjoy it!



## easy use in ide

### vscode

via https://marketplace.visualstudio.com/items?itemName=cyberbiont.vscode-open-in-typora

### jetbrains

**setting external tools**

path: Setting/Tools/External Tools

```shell
Name: Typora
Description: open markdown document in typora

# on macOS with system program launcher "open -a"
# if you want to boot on another operating system
# you should find the executable file path and replace "open -a Typora"
Program: open
Arguments: -a Typora $FileRelativePath$
Working directory: $ProjectFileDir$
```

Then in the right menu you can find external tool/Typora and open file with it