## 目录(Dirvish)
### 1.直接使用 :Dirvish 命令
| 命令 | 作用 |
|------|------|
| `:Dirvish` | 打开当前文件所在的目录 |
| `:Dirvish ~/` | 打开指定目录（家目录） |
| `:Dirvish /etc/` | 打开任意目录 |

### 2.用 Vim 原生的"编辑目录"方式
Dirvish 安装后会接管 Vim 默认的目录浏览器（netrw），所以这些操作都会进入 Dirvish 界面：
| 命令 | 作用 |
|------|------|
| `:e .` | 编辑当前目录 |
| `:e ~/` | 编辑家目录 |
| `:Explore` | `:Ex` 也可以，原生目录浏览命令 |

### 3. 进去之后怎么用
一旦进入 Dirvish 窗口：

| 按键 | 作用 |
|------|------|
| `~` | 跳到家目录 |
| `%` | 新建文件（init/init-plugins.vim:80） |
| `Enter` | 打开光标所在文件 / 进入光标所在子目录 |
| `-` | 返回上一级目录 |
| `q` 或 `:q` | 关闭 |

## TAB

| 按键  | 底层命令 | 作用 |
|------|------|------|
| \<leader>tc	 | :tabnew	| Vim 原生（新建 tab）|
| \<leader>tq	 | :tabclose | Vim 原生（关闭 tab） |
| \<leader>tn	 | :tabnext	| Vim 原生（下一个 tab）|
| \<leader>tp	 | :tabprev	| Vim 原生（上一个 tab）|
| \<leader>to	 | :tabonly	| Vim 原生（关闭其他所有 tab）|
| gt | | 下一个tab|
| gT | | 上一个tab|
| {n}gt | | 跳到第n个tab(如 3gt)|
| Ctrl + PageDown | | 下一个tab|
| Ctrl + PageUp | | 下一个tab|
