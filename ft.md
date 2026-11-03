## window 安装 gVim
step 1：下载 gVim
  - 访问 [https://github.com/vim/vim-win32-installer/releases](https://github.com/vim/vim-win32-installer/releases)
step 2：默认安装 gVim
  - 默认安装即可
step 3：安装
  - 访问 [https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim](https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim)
  - 保存文件到：`C:\Users\你的用户名\vimfiles\autoload\plug.vim`
  - 没有 autoload 文件夹就自己新建

step 4: 配置
  - 重命名vimrc修改为_vimrc（不修改文件名，有些功能不好使）
  - 复制source目录到 gVim 安装目录
  - 保存文件到 gVim 安装目录

step 5: 安装插件
  - gVim 末行模式下执行命令 :PlugInstall

