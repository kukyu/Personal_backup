# 新建文件删除 windows 快捷方式后缀

## 1

在“运行”里，输入“regedit”，打开注册表编辑器;

## 2

依次展开 `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer`

点击选中 Explorer 项目，在右侧窗口找到并双击 link 键值项，修改为全0

![link](Pictures/link.jpg)
