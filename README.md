# This is my st config for ArchLinux

## 补丁列表

- copyout.sh													//实现命令输出内容的复制
- st-alpha-0.8.2.diff 								        			 //  端透明
- st-anysize-0.8.1.diff												 //全屏
- st-clipboard-20180309-c5ba9c0.diff								  //浏览器与终端剪贴板的切换
- st-externalpipe-0.8.2.diff										  //通过管道读写st的屏幕输出
- st-focus-20200731-patch_alpha.diff								 //实现获得焦点与失去焦点的透明效果
- st-hidecursor-0.8.3.diff											//再失去焦点是不显示光标
- st-ligatures-alpha-scrollback-20200430-0.8.3.diff						  //添加了一些对连字符的支持
- st-rightclickpaste-0.8.2.diff										   //右键粘贴
- st-scrollback-20200419-72e3f6c.diff								 //shift+{pageup/pagedown}滚动终端
- st-scrollback-mouse-20191024-a2c479c.diff							//shift+鼠标滚轮滚动终端
- st-scrollback-mouse-altscreen-20200416-5703aa0.diff				    //鼠标滚轮滚动终端

### 说明

> alpha 补丁需配合窗口渲染器使用 ，如 (picom)
>
> 额外字体支持: Fira Code

## 安装

```shell
git clone https://github.com/mnmnmssd/my-st-config.git
cd my-st-config
sudo make clean install
```

## 部分快捷键

- ALT + y			复制终端上输出的URL (上下键选择)
- ALT + l             打开终端上输出的URL (上下键选择)
- ALT + c            打开终端上命令的输出 (上下键选择)

# loading...

