# Octopress-Emacs

本插件修改自[gfreezy/octopress-emacs](https://github.com/gfreezy/octopress-emacs "gfreezy/octopress-emacs").

### Contact Me
* Email: venmos[at]gmail.com
* Jabber: venmos[at]gmail.com
* Blog: http://venmos.com

### 功能

使用本插件你可以直接在Emacs中操作Octopress,包括:

* rake new post -> octopress-new-post
* rake new page -> octopress-new-page
* rake generate -> octopress-generate
* rake deploy -> octopress-deploy
* rake gen_deploy -> octopress-gen-deploy

### 注意:

* 本插件需要使用Bash与RVM;
* 第一次使用需修改`octopress.el`中的Ocotpress路径;
* 如你的RVM有特别设置,也需在`octopress.el`中做相应修改;
* 在Mac OS X Lion 10.7.4 or Emacs 24.2.50.1下测试通过.

### 使用:

* M-x octopress-new-post     创建并打开编辑一个新Post;
* M-x octopress-new-page     创建并打开编辑一个新Page;
* M-x octopress-generate     转换HTML;
* M-x octopress-deploy       发布到服务器;
* M-x octopress_gen_deploy   转换并发布到服务器;
