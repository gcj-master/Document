# windows好用的工具类软件

1. Ditto 剪贴板增强工具： https://ditto-cp.sourceforge.io
2. 最强截图工具：https://zh.snipaste.com/
3. MarkDown：https://obsidian.md/
4. 制作启动盘：https://rufus.ie/zh/
5. windows系统因权限无法删除的文件，建立.txt文件，复制以下代码然后把文件后缀名改为.bat，将无法删除的文件拖进这个.bat文件就可以删除了。
    
    >`DEL /F /A /Q \\?\%1`  
    >`RD /S /Q \\?\%1`
