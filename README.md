# 一、【安装准备】
### 1．在网盘下载以下软件。
![](https://github.com/xinqi3050/unity/blob/master/1.png)
### 2. 首先安装Unity3d开发平台
（1）UnitySetup64-5.6.2f1

（2）UnityStandardAssetsSetup-5.6.2f1。
### 3．再安装JAVA开发平台
（1）jdk-8u144-windows-i586_8.0.1440.1

（2）android-sdk_r24.4.1-windows

（3）UnitySetup-Android-Support-for-Editor-5.6.2f1
# 二、【具体实验步骤】
### 第一步：
下载UnitySetup64-5.6.2fl，保留5G左右的硬盘空间，准备安装。安装过程多是直接点击“下一步”，启动时，先要注册用户，输入帐号和密码。
 ![](https://github.com/xinqi3050/unity/blob/master/2.png)
### 2. 首先安装Unity3d开发平台
### 第二步：
关闭UnitySetup64-5.6.2fl后，开始安装Andriod开发环境，目的是生成手机的apk文件。

* 1．Unity3d标准资源包
UnityStandardAssetsSetup-5.6.2f1资源包

* 2．Jdk (安装JAVA开发包)
软件：jdk-8u144-windows-i586_8.0.1440.1

### 第三步：
由于我的软件之前就已经安装好了，所以就没有具体多加说明，所有的安装步骤都可以使用默认，路径可选择更改，但需记住位置，后面会使用到。
**注意：保存的文件夹名字一定要用英文形式**
### 第四步：
配置环境变量的配置

#### 1、右键我的电脑，点击最下面的属性，之后再弹框里点击高级系统设置，再点击环境变量
![](https://github.com/xinqi3050/unity/blob/master/3.png)
### 2. 首先安装Unity3d开发平台
#### 2、点击新建

(1)新建->变量名"JAVA_HOME"，变量值f:jdk（即JDK的安装路径）
![](https://github.com/xinqi3050/unity/blob/master/4.png)
### 2. 首先安装Unity3d开发平台
(2)编辑->变量名"Path"，在原变量值的最后面加上 %JAVA_HOME%\bin之后点击确定
![](https://github.com/xinqi3050/unity/blob/master/5.png)
### 2. 首先安装Unity3d开发平台
接下来进行验证，看是否成功安装了java;打开cmd，输入 java 观察是否有输出

### 第五步:
安装sdk（Andriod开发包），解压android-sdk_r24.4.1-windows.rar
![](https://github.com/xinqi3050/unity/blob/master/6.png)
### 2. 首先安装Unity3d开发平台
运行SDK Manager.exe,安装SDK文件要更新17个包，约半小时才能完成。
![](https://github.com/xinqi3050/unity/blob/master/7.png)
### 2. 首先安装Unity3d开发平台
### 第六步：
配置开发环境

1、打开unity，新建一个项目，打开Edit-Preferences选项

SDK地址：点击Browse，找到刚刚复制的android-sdk-windows文件夹所在的路径

点击Browse，选择路径文件夹，JDK地址：g:/jdk1.8
![](https://github.com/xinqi3050/unity/blob/master/8.png)
### 2. 首先安装Unity3d开发平台
2、切换平台为安卓Android平台
![](https://github.com/xinqi3050/unity/blob/master/9.png)
### 2. 首先安装Unity3d开发平台
切换，点击Player settings修改Other Settings中BundleIdentifier的com.Company.ProductName为自己的自定义的，例如：com.xinqi.me，修改完成后，点击Build。
 
保存成apk文件
![](https://github.com/xinqi3050/unity/blob/master/10.png)
# [录屏](https://github.com/xinqi3050/unity/blob/master/171013050%E6%9E%97%E6%96%B0%E6%A3%8B.mp4)
