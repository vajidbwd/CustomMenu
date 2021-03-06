CustomMenu是一个自定义的控件，可以帮助你快速创建Menu

# 功能

* 只用左菜单
* 只用右菜单
* 左右菜单一起用
* 左右菜单都不用,CustomMenu相当于是一个布局

## 示例

* 仅使用左菜单

  ![](https://github.com/flyfei/CustomMenu/blob/master/resources/only_left_menu.gif)

* 仅使用右菜单

  ![](https://github.com/flyfei/CustomMenu/blob/master/resources/only_right_menu.gif)

* 使用左右菜单

  ![](https://github.com/flyfei/CustomMenu/blob/master/resources/double_menu.gif)

* 不使用菜单

  ![](https://github.com/flyfei/CustomMenu/blob/master/resources/no_menu.gif)


## 使用说明


```
CustomMenu customMenu = new CustomMenu(this);

//设置中间布局
ImageView contentView = new ImageView(this);
contentView.setBackgroundResource(R.drawable.main_view);
customMenu.setContentView(contentView);

//设置左菜单
ImageView leftMenu = new ImageView(this);
leftMenu.setBackgroundResource(R.drawable.left_view);
customMenu.setLeftMenu(leftMenu);

//设置右菜单
ImageView rightMenu = new ImageView(this);
rightMenu.setBackgroundResource(R.drawable.left_view);
customMenu.setRightMenu(rightMenu);

//打开左菜单
customMenu.openLeftMenuIfPossible();

//打开右菜单
customMenu.openRightMenuIfPossible();

//关闭菜单
customMenu.closeMenu();

//获取状态
customMenu.getState()

//设置右侧阴影
setRightShadow(int resId);
setRightShadow(Drawable shadowRight);

//设置左侧阴影
setLeftShadow(int resId);
setLeftShadow(Drawable shadowLeft);
```

* [阴影图片资源](https://github.com/flyfei/CustomMenu/tree/master/resources/shadowImg)

## Latest Version


[Download](https://github.com/flyfei/CustomMenu/wiki)


## 反馈

如果发现问题，请 emailto:zhaotengfei9@gmail.com



