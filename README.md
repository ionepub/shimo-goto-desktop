# shimo-goto-desktop

这是一个chrome浏览器扩展程序。

> 
> 可能有些人会有跟我一样的感觉，每次打开石墨( https://shimo.im )的首页，总觉得不舒服，非得要点击右上角 ` 进入石墨 ` 按钮才能进入到石墨桌面去，虽然只是多了一次点击，但对于打开关闭页面频次较高的我来说，这需要点代价。
>

于是有了这样一个插件。

它的功能非常简单：

**打开石墨文档的首页时，让页面自动重定向到石墨桌面。**

当然，如果没有登录，会跳转到登陆页面去，登录成功之后，会重定向到石墨桌面( https://shimo.im/desktop )去。

## 使用方法

### Google chrome

目前没有发布到谷歌浏览器插件平台，只能用开发者模式安装。

- 1. 下载 [master.zip](https://github.com/ionepub/shimo-goto-desktop/archive/master.zip "master.zip")
- 2. 解压到一个不常用的文件夹中，如D盘
- 3. 打开谷歌浏览器，在地址栏中输入 ` chrome://extensions  ` 进入插件页面，或从右上角菜单进入更多工具-扩展程序
- 4. 勾选开发者模式，点击“加载正在开发的扩展程序”按钮
- 5. 选择步骤2中扩展程序存放的文件夹即可

### QQ浏览器

- 下载shimo-goto-desktop.crx文件
- 打开QQ浏览器，在地址栏中输入 ` qqbrowser://extensions/manage  ` 进入插件页面，或从右上角菜单进入应用中心-管理我的应用
- 将shimo-goto-desktop.crx文件拖动到浏览器中，提示安装
- 安装完成之后即可使用

### 其他浏览器

凡带有chrome内核的浏览器一般都支持此插件，如果直接安装crx文件失败，可参考谷歌浏览器安装方法