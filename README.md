Cura 2.x 中文语言包（汉化）
=

Cura国内用户使用版本较低，大多数是在使用cura14.想15.x版，没有与国外软件升级跟进，其一根本原因就是汉化程序未及时跟进，官方版本已到达2.6，且2.7已进入beta阶段，在使用过程中发现国内汉化教程比较少，而2.x版本的Cura采用多语言版本开发，语言包独立与程序本身，谁都可以为此软件的汉化贡献一份力量，所以在最后面会加上语言包修改教程，望英语好的同学也来贡献一份力量~

软件汉化
-----
下载本项目代码（代码类别右上角的绿色按钮，点开点击下载zip包），找到软件安装目录resources，将下载的代码复制到resources同级目录下，会提示文件覆盖，同意即可，再次重启后在设置界面会出现简体中文选项，选择重启即可出现中文界面。

修改说明
-
1、修改文件resources/qml/Preferences/GeneralPage.qml 
```append({ text: "Français", code: "fr" })
append({ text: "Italiano", code: "it" })
append({ text: "简体中文", code: "zh_CN" })
append({ text: "日本語", code: "jp" })
```
增加了配置中简体中文的选项

2、在i18n文件加下新增zh_CN语言文件，其中po为语言源文件，LC_MESSAGES文件夹下的mo是编译后的语言文件

百度网盘下载地址：https://pan.baidu.com/s/1cJDZXG 密码：p8xk

贡献代码
-
1. 基础知识 po语言文件是什么以及多语言实现原理 语言文件.po .pot和.mo简介及汉化 http://shandian.biz/278.html
2. po文件编辑器poedit https://poedit.net/ 修改po文件保存后自动生成mo文件
3. 克隆项目到本地
```git clone https://github.com/yuzhewo/cura2.x-Chinese.git```
4. 修改文件生成的mo文件移动到LC_MESSAGES文件夹中，本地重启软件测试并提交
5. 提交更改到GitHub

特别感谢
-
* PCDotFan https://github.com/PCDotFan
* POEdit https://poedit.net/ 


