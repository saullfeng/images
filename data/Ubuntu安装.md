###下载Ubuntu

ubuntu下载地址：
　中科大源 
      http://mirrors.ustc.edu.cn/ubuntu-releases/
　阿里云开源镜像站 
      http://mirrors.aliyun.com/ubuntu-releases/
　兰州大学开源镜像站 
      http://mirror.lzu.edu.cn/ubuntu-releases/
　北京理工大学开源
      http://mirror.bit.edu.cn/ubuntu-releases/
　浙江大学 
      http://mirrors.zju.edu.cn/ubuntu-releases/
也可以将16升级到指定版本

### 安装过程

####2.1 VMware添加虚拟机

##### （1） 打开VMware，创建新的虚拟机

 

![image-20210902173635801](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902173635801.png)

##### （2）选择“自定义（高级）”

![image-20210902173702676](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902173702676.png)

##### （3）选择兼容性，（直接默认就行）

![image-20210902173744292](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902173744292.png)

##### （4）选择“稍后安装操作系统”

![image-20210902173808335](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902173808335.png)



##### （5）选择“Linux”，“Ubuntu 64位”





![image-20210902173905238](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902173905238.png)

#####（6）根据需要更改虚拟机名称及存放位置（最好放在SSD里）



![设置名称(不是虚拟机系统内的用户名)和系统文件存储位置](https://img-blog.csdnimg.cn/20200214212726414.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQ0NzIzNzcz,size_16,color_FFFFFF,t_70)



#####（7）处理器配置（根据自己的电脑的配置选择）

处理器数量：2 （相当于几个核）

每个处理器内核数量：2 （每个核多少线程）



![image-20210902174117682](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174117682.png)



#####（8）配置虚拟机内存（4G往上吧）



![image-20210902174148638](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174148638.png)

#####（9）直接一路next就行了



![image-20210902174159360](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174159360.png)



![image-20210902174213278](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174213278.png)



![image-20210902174221231](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174221231.png)





![image-20210902174228695](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174228695.png)

#####（10）指定磁盘容量：30G往上（安装完系统会占不少位置，各种库也很占磁盘），【记得选：将虚拟磁盘存储为单个文件】

##### （11）还有几个框，直接“下一步”



![image-20210902174305214](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174305214.png)

![image-20210902174314467](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174314467.png)

####

#####（12）添加完成，你会看到这样的信息

![image-20210902174409414](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174409414.png)

#####（13）点击上图中的`编辑虚拟机设置`选项

![image-20210902174752686](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174752686.png)

#####（14） 选中“CD/DVD(SATA)”，选择“使用ISO映像文件”，点击“浏览”，找到前面下载好的Ubuntu ISO文件，点击“确定”，至此配置虚拟机过程结束，接下来安装Ubuntu系统

![image-20210902174832021](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902174832021.png)

####2.2 安装Ubuntu系统

#####（1） 点击`开启此虚拟机`

##### （2）点击`install Ubuntu`



![image-20210902175008099](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902175008099.png)



![image-20210902175133351](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902175133351.png)

![image-20210902175149518](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902175149518.png)





#####（3） 选择`Erase disk and install Ubuntu`，点击`Install Now`; 在弹出的窗口中选择`Continue`

#####（4） 选地图上的`上海时区`

#####（5） 选择键盘布局，`continue`在在框的右边（第一次打开虚拟机的时候分辨率低，可能看不到那个按钮，把框向左拉一下）

#####（6） 设置电脑名称和账号密码，点击即可开始安装系统

#####（7） 安装完成后会有如下提示，根据提示重启电脑即可

![image-20210902180443834](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902180443834.png)

#####（8）重启后，如下图。

![image-20210902190011833](C:\Users\solfeng\AppData\Roaming\Typora\typora-user-images\image-20210902190011833.png)
