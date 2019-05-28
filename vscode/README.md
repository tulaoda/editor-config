# VS code 配置信息

## 1. 配置文件

**settings.json** 文件，使用该文件中的内容替换默认的 setting.json 中的内容即可。在 MacOS 下按 “command + ,” 键打开配置页，默认为 ui 形式，点击标题栏右边的 “{}” 图标即可打开 json 形式的文件。

其中
- `// Base Settings` 注释下面的部分是 vscode 默认的配置项
- `// Base Plugin Settings` 下面的部分是初始安装的插件的配置
- `// Langulage Settings` 下是针对不同编程语言的配置
- `// Download Plugin Settings` 下是自定义安装的插件的配置信息

添加插件最好是先确认插件功能。

<br/>

---

<br/>

## 2. 自定义快捷键

有时候觉得 vscode 的 [原始快捷键](./keyboard-shortcuts-mac.pdf) 还是很蛋疼的，所以我针对自己的使用情况做了些更改。

将默认的 **keybindings.json** 中的内容替换为项目中对应文件的内容即可。MacOS 中按组合键 “command k + command s” 即可查看全部的快捷键，点击标题栏右边的 “{}” 图标即可打开 json 形式的文件。

| 快捷键 | 功能描述 | 初始快捷键 | 初始功能 |
| :---: | :-----: | :------: | :--:|
| 回车键 | 打开文件 | 无 | 更改文件名 |

<br/>

---

<br/>

## 3. 插件列表

### 通用
1. 中文包：不多说
2. [ESLint](https://eslint.org/): 不多说
3. open in browser: 不多说
4. [Beautiful](https://github.com/HookyQR/VSCodeBeautify/blob/master/Settings.md): 格式化代码的扩展，可以自己自定义格式化，但是自己尝试的时候发现没有默认的 Format 好用 = =
5. Prettier - Code formatter: 格式化代码的预设，比 Beautiful 好用得多
6. Code Runner: 测试你的代码块，并输出到 vscode 中
7. vscode-icon: 为你的文件添加漂亮的 icon
8. Bracket Pair Colorize: 括号颜色区分和匹配
9. Auto Rename Tag: 修改标签，自动修改对应的另一个标签
10. Auto Close Tag: 自动补全尾标签
11. Path Intellisense: 路径自动补全，vscode 内部已经实现了基本功能，但要在项目中拓展路径映射时十分好用
12. bracket-padder: 括号中自动匹配空格，写代码很舒服
13. Color Info: 直接在编辑器中查看颜色信息
14. Document This: 快速生成标准注释

### Git
1. Git History: 查看 Git 提交的记录，文件的 Git 提交记录等
2. Git Graph: 一个更全面的 Git 图形化界面

### ES6 +
1. JavaScript(ES6) code snippets: ES6 新特性的补全

### HTML
1. HTML Snippets: 目前还不知道有什么用

### Vue 开发专用
1. [Vetur](https://vuejs.github.io/vetur/): 提供 Vue 的语法高亮、输入提示、Lint、Emmet 等功能
2. Vue VSCode Snippets: Vue 的补全