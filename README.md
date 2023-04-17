<img src="./pics/icon.png" align="right" />

# MasterLazyVim 🏄

## 是什么🤔

Lazy is an amazing package for neovim. It has auto-lazy-loading. auto installation of missing plugins, an amazing UI, and other awesome features!

packer 其使用的方式

lazy.nvim的便利 UI

https://www.youtube.com/watch?v=6vBKe2mI_9c

LazyVim 的出现可以说是将主流 IDE 和 Vim 的优点有机地结合在一起，使得它既具备强大的编辑和编程功能，同时也具备交互体验和开发效率。因此，使用 LazyVim 可以让你更加高效地完成编程工作，并且能够享受使用 Vim 带来的编辑效率和快乐。


https://zhuanlan.zhihu.com/p/608322089

来替换掉你的vim，打造堪比IDE的编辑工具

https://www.githubs.cn/projects/583706111-lazyvim

- tmux

https://www.fosslinux.com/106799/managing-tmux-plugins-with-tmux-plugin-manager.htm

https://github.com/tmux-plugins/tpm

```
# act like vim
setw -g mode-keys vi
bind-key h select-pane -L
bind-key j select-pane -D
bind-key k select-pane -U
bind-key l select-pane -R
bind-key -r C-h select-window -t :-
bind-key -r C-l select-window -t :+

# List of plugins
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'dracula/tmux'

set -g @dracula-show-powerline true
set -g @dracula-fixed-location "NYC"
set -g @dracula-plugins "weather"
set -g @dracula-show-flags true
set -g @dracula-show-left-icon session
set -g status-position top

# Initialize TMUX plugin manager (keep this line at the very bottom of tmux.conf)
run '~/.tmux/plugins/tpm/tpm'
```

## Tips🔐

[vim原生快捷键](https://devhints.io/vim)

## 步骤

1. 运行`:checkhealth`

2. 进入配置目录.config/nvim

3. mason面板上的图标不见了

4. 

0:00 Introduction
0:24 LazyVim Installation
1:35 Show which-key
2:11 Add TypeScript Support 
3:10 Find Files via Telescope
3:38 Leap.nvim Plugin
3:55 LSP Features
4:14 Search Grep via Telescope
4:32 Diagnostics
5:02 Colorscheme Picker
5:12 Switch Buffers
5:39 Splits
6:05 Todo Plugin
6:40 Autocompletion and Snippets
7:40 Find Keymaps
7:52 Lazy.nvim Plugin
8:34 Toggle Numbers
8:45 Global Search Replace
9:34 Lazygit Plugin
9:58 Terminal Plugin
10:49 Add Custom Option
11:30 Add Custom Keymap
12:46 Switch Default Colorscheme
13:59 Add New Plugin
15:11 Update Built-in Plugin
15:58 Disable Built-in Plugin
16:36 Conclusion