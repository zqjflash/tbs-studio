### 一、TBS Studio简介

#### 1.1 TBS Studio是什么

TBS Studio是面向基于TBS的Web开发者和移动应用开发商（包括微信、手Q，三方App等）打造的开发服务整体解决方案，以提升广大开发者在真机环境下的开发效率，并帮助开发者分析和优化网页的设计，主要功能有网页Inspector调试，网页性能分析等。

#### 1.2 TBS Studio开发背景介绍

TBS Studio的前身是TBS下的WebView Inspector网页调试工具，当中经历几个阶段的演进：

 * 第一阶段：需要手动安装TBS调试版内核，并且需要PC端使用python脚本，安装代价大；

 * 第二阶段：TBS2.0之后版本打开debug调试页面，勾选inspector开关选项重启，很多App没有入口可以打开调试页面；
 
 * 第三阶段：经过不断改进和优化，最终形成TBS studio开发服务的整体解决方案。
 
后续会基于该框架不断扩充对开发者的引导和帮助信息，帮助开发者快速解决问题，提升开发效率，并提升Web开发的质量。

#### 1.3 TBS Studio功能特性

 1 自动检测手机与PC的连接；
 2 自动检测网页是否可进行Inspect调试；
 3 自动引导开发者打开Inspector调试开关；
 4 一键开启Inspector调试，无需打开浏览器输入URL，方便快捷；
 5 扩展X5内核独有Inspect选项，方便页面分析和优化；
 6 真机远程Inspector调试。 

#### 1.4 TBS Studio 启动调试流程图

![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio1.png)

#### 1.5 TBS Studio包下载

 [Windows64位下载地址](http://mcaredown.3g.qq.com/browser/tes/TBS_Studio_v1.1.zip).
 
 [Windows32位下载地址](http://mcaredown.3g.qq.com/browser/tes/TBS_Studio_32bit_v1.1.zip).
 
 [Mac版下载地址](http://mcaredown.3g.qq.com/browser/tes/TBSStudio_mac_v1.1.1.zip).
 
### 二、TBS Studio安装和启动

#### 2.1 运行环境

 * PC环境: 当前支持Windows和mac操作系统。
 * 手机环境：Android 4.0+，机型包括华为，小米，三星等主流机型。
 * 调试宿主App：微信、手Q、QQ音乐、QZone、京东等 

#### 2.2 安装说明

免安装。

注：如果存在无法使用的情况，请将TBS Studio放置到英文目录下重试。

### 三、TBS Studio工具使用

#### 3.1 启动应用

 1 双击启动TBS Studio.exe 
 
 2 选择调试设置Tab，启动检测，示意如下： 

 ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio2.png)

#### 3.2 TBS Studio 调试设置

 1 请连接手机，允许USB调试；
 
  * 检测成功，示意如下：
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio3.png)
   
  * 检测失败请重新检测，示意如下：
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio4.png)

 2 设定/修改调试目标App；
 
  * 弹出调试App提示
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio5.png)
   
  * 点击确认，通过step2，示意如下：
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio6.png)
   
  * 点击取消，失败提示请重新检测，示意如下：
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio7.png)
   
 3 检测是否支持TBS调试；
 
  * 点击确定关闭调试App
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio8.png)
   
  * 自动下载、自动安装、自动打开TBS Studio Client客户端
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio9.png)
   
  * 自动安装TBS内核，请关注手机安装过程
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio10.png)
   
  * 自动拉取待调试的App，请访问一个webview页面，再点击确认
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio11.png)
   
  * 调试App确认打开webview页面，点击确认
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio12.png)
   
 4 设定TBS调试状态。
 
  * 请确认打开调试开关，建议勾选永久生效，不勾选默认只保留一天
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio4-1.png)
   
  * 点击打开待调试App，访问webview页面，示意如下：
  
   ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio4-2.png)
   
#### 3.3 TBS Studio 启动调试

 1 点击启动调试按钮，示意如下：
 
  ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio14.png)
  
 2 找到对应App webview调试页面，示意如下：
 
  ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio15.png)
  
 3 进入Developer Tools调试界面：示意如下：
 
  ![img](http://res.imtt.qq.com/tbs_inspect/tbsstudio/tbsstudio16.png)
  
### 四、TBS Studio工具日志说明

 1 在使用过程中如果发生了问题，可以尝试获取日志文件向我们反馈
 
  日志文件存放位置如下（UserName是当前登录的用户名称）：
  
  ```js
   C:\Users\UserName\AppData\Local\tbs_debug\User Data\Default\tbs_debug.log
  ```
### 五、FAQ

 1 微信调试时，TBS内核大于2.0且小于最新内核时如何开启Inspector功能？
    
  * 在“X5调试页面”上，点击进入“信息”Tab。
  * 找到TBS settings栏目，勾选“是否打开TBS内核Inspector调试功能”，然后点击确认，进程自动退出。
  * 重新打开Web页面，使用Inspector页面调试功能。 
  
 2 没有tbs内核的手Q，第一次跳转到debugtbs.qq.com的时候要如何操作？
 
  * 点击“安装线上TBS内核”，等待下载和安装TBS内核。
  * TBS内核安装成功后，点击确认重启再次扫码进入Inspect中转页面。

 3 电脑死活adb连接不成功？

  * 请确保USB连线能正常连通PC和手机。简单确认方法：手机状态栏显示为充电状态。
  * 请确保PC的USB驱动已正常安装，可以在控制面板“设备管理器” “通用串行总线控制器”中确认无异常USB设备显示。
  * 点击重置，再次“启动检测”。

### 六 发布版本变化说明

 * 2016-09-19 TBS Studio1.0.0 正式发布。
 * 2016-11-16 TBS Studio1.1.0 版本发布，支持QQ浏览器调试。

### 特别鸣谢：

TBS内核开发同学大力支持







