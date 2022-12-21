修复了原作者的权限错误和js错误，格式化部分代码

### 下载源码方法:

 ```Brach
    git clone https://github.com/sirpdboy/luci-app-netdata package/luci-app-netdata
    make menuconfig
 ``` 
### 配置菜单

 ```Brach
    make menuconfig
	# 找到 LuCI -> Applications, 选择 luci-app-netdata, 保存后退出。
 ``` 
 
### 编译

 ```Brach 
    # 编译固件
    make package/luci-app-netdata/compile V=s
 ```
