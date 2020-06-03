<p align="center">
    <img src="https://cdn.jsdelivr.net/gh/ZainCheung/helper-618/img/logo.png"
        height="310">
</p>
<p align="center">
    <img alt="Version" src="https://img.shields.io/badge/release-1.3.0-blue"/>
<a href="https://github.com/ZainCheung"><img alt="Author" src="https://img.shields.io/badge/author-ZainCheung-blueviolet"/></a>
  <img alt="Vue" src="https://img.shields.io/badge/Auto.js-4.1.1-success"/>
</p>

[💡 快速开始](#快速开始)

[📚 功能](#功能)

[🎁 下载地址](#下载地址)

[📷 运行截图](#运行截图)

[🔔 注意事项](#注意事项)

[🔒 安全性](#安全性)

[📋 常见问题](#常见问题)

[👻 责任说明](#责任说明)

# 快速开始
1. 下载并安装app；
2. 安装成功先不要打开，去设置->应用->权限->找到“叠蛋糕全自动”，然后进去把悬浮窗权限打开；
3. 回到桌面，打开app；
4. 根据app弹窗提示选择适合的速度；
5. app会自动跳到无障碍服务，你需要在里面找到这个app，并且打开它的无障碍开关；
6. 静等一到两秒，悬浮窗里会出现“正在进入个人中心”，然后app将会自动打开京东并跳转到指定的活动页面；
7. 等待app将任务做完。

# 功能
## 京东
1. 可以选择执行速度，避免脚本执行出错；
2. 自动打开京东进入活动任务页面；
3. 自动完成签到；
4. 自动完成快速浏览商品任务；
5. 自动完成8秒浏览任务；
6. 自动完成加购；
7. 自动检查运行出错并纠正。

## 淘宝
1. 可以选择执行速度，避免脚本执行出错；
2. 自动打开淘宝进入活动任务页面（暂时还需要手动点击）；
3. 自动完成签到；
4. 自动完成兑换喵币任务；
5. 自动完成15秒浏览任务。

# 下载地址
## 京东叠蛋糕全自动app所有发布版本以及源码
蓝奏云地址：https://zaincheung.lanzous.com/b00tkff6b
密码:hcm1

天翼云地址：https://cloud.189.cn/t/QJ3mQvBRFJBz
访问码:bi7l

## 淘宝列车全自动app所有发布版本以及源码
蓝奏云地址：https://zaincheung.lanzous.com/b00tkz0vg
密码：3fod

天翼云地址：https://cloud.189.cn/t/E3mMBjmYJRF3
访问码:un2b

## 脚本运行环境--Auto.js
蓝奏云地址：https://zaincheung.lanzous.com/id4pe9a

天翼云地址：https://cloud.189.cn/t/YJF7na7faM7n
访问码:8yjy

# 运行截图

![](https://cdn.jsdelivr.net/gh/ZainCheung/helper-618/img/jd.png)

![](https://cdn.jsdelivr.net/gh/ZainCheung/helper-618/img/jdhelper.png)

![](https://cdn.jsdelivr.net/gh/ZainCheung/helper-618/img/淘宝618.png)

# 注意事项

1. app会自动帮你打开京东和淘宝，但是淘宝打开后你需要手动点进活动页面，就是瓜分10亿那个入口；
2. 如果淘宝app是第一次使用，还需要先进去给你的列车升级到2级以上，不然每次进去都有弹窗；
3. 如果你选择快速模式而出现了问题，可以重新启动脚本，选择较慢的速度执行；
4. 运行前需要给软件打开无障碍服务以及悬浮窗权限；
5. 有时候打开app没有反应的话可以关掉重新打开一次；
6. 收菜的任务还是没有找到解决办法，有了解的方便的话可以告知一下，非常感谢；
7. 如果拿到脚本运行出错，请检查一下自己所用的Autojs版本，如有不同可以下载本项目提供的安装包。

# 安全性
删除了APP不需要的权限，只保留了提示框权限和访问设置权限（帮助打开无障碍服务），加了安全签名（为了不让手机误报病毒）并且通过了32个杀毒引擎的测毒。


# 常见问题
**1. 为什么app在打开京东后就没有反应了咋回事？**

答：在使用之前你需要先关掉京东的后台，确保app打开时是从首页进去的，而不是你的购物车页面或者商品页面。


**2. 纠正功能为什么没有让我回到正确的页面？**

答：纠正功能主要是为了防止弹出窗口，以及浏览8秒商品的长时间等待期间误触而新增的，脚本正在加购或者快速浏览时请不要干扰它，它干起活来很专注（滑稽）。


**3. 加购任务为什么执行完一次就回到桌面了？**

答：因为任务完成后执行了返回操作，然而系统给它指向了桌面，不过这些问题已经在新版本里解决了，新增的纠正功能可以自动回到活动页面继续刷任务。需要注意的是回到桌面后大约会等待5秒左右才可以回去,这是因为在第二次纠正前还有五次第一次纠正，所以还烦请稍稍耐心等待一下，不要见没有回去以为出问题就草草关掉了。


**4. 单靠这个app可以完成所有的任务吗？**

答：除了邀请好友助力以及AR游戏等任务无法帮你完成，其他已经全部覆盖，目前可以做到一次打开，刷完所有非主观任务，本人测试可以做完50次不断开（2020.05.26）。


**5. 为什么要用app而不是去调用接口一键完成所有任务？**

答：app运行的原理就是模拟你对屏幕的操作，这样JD查不到任何违规行为，如果是要通过调用接口挂多个号，，有黑号的风险，我觉得为了这个活动没必要冒这个风险。


**6. 可以给多个jd号刷任务么？**

答：如果有应用分身可以借助分身，然后app启动时会弹出选择分身。如果不用分身，在上一个账号做完所有任务后，切换到下一个账号，多个账号轮流切换，虽然稍有些麻烦，但比较保险。

**更多问题欢迎提出issues，或者前往首发论坛查看**

淘宝列车：https://www.52pojie.cn/thread-1189363-1-1.html

京东叠蛋糕：https://www.52pojie.cn/thread-1186000-1-1.html

淘宝+京东集成尝鲜版：https://www.52pojie.cn/thread-1190625-1-1.html

# 责任说明
该脚本以及软件仅用于学习开发,勿用于商业及非法用途，如产生法律纠纷与本人无关。
