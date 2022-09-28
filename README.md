# 探究自动打卡的原理与对抗策略

## What's New?

### Sep 29th

现在可以把打卡结果以邮件形式发送给你，防止突然失效
以QQ邮箱为例：
1. 设置-账户，点击获取并记录你的口令
![](images/email.jpg)
3. 打开本仓库的Settings-Secrets-Actions，添加名为E_MAIL和TOKEN的项，值分别填上你的邮箱地址和第一步获得的口令
![](images/secrets.jpg)


### Jul 8th

支持自动填写表单新增的实习选项。
https://github.com/vtu81/ZJU-Clock-In/blob/c4ea9c29fef110f1c3a7abf304f5001a58d7d2ed/clock-in.py#L125

### May 7th

<s>现已支持验证码识别+自动填写～</s>

目前打卡验证码已取消，相关代码已经注释掉了：
https://github.com/vtu81/ZJU-Clock-In/blob/c4ea9c29fef110f1c3a7abf304f5001a58d7d2ed/clock-in.py#L122

## 使用须知

ZJU 打卡脚本参考样例 by：Tenderness

**免责声明：本脚本仅供内部学习研究使用，请勿将其用作任何实际用途，否则后果自负，作者将不为其承担任何法律责任，下载后请24h内删除**

**本脚本使用API均为开放API， 如需学习或测试请查看仓库内的doc.md和doc.pdf，注意，请勿将其用于现实生活中的健康打卡操作**

**同时欢迎有志之士一同研究对抗自动打卡的策略， 共同协助学校完善打卡系统安全性**

**新冠疫情时刻都会卷土重来，请大家不要放松警惕，坚持手动上报健康信息，不要使用任何自动化工具，投机取巧是可耻行为，我们要协力共抗新冠。**
