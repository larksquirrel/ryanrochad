最新版本：瑞恩罗恰德2.0.zip

2025/08/19
1. 更新代码及github链接：
    a. 上传“瑞恩罗恰德.rar”文件至github，生成链接为：https://larksquirrel.github.io/ryanrochad/；
    b. 修改home.html文件名为index.html，作为主界面；
    c. 修改各文件中的原跳转至home.html的代码为index.html。
2. 更新DSN：
    a. 更新CNAME记录：停用原值lina8bell.github.io，换用larksquirrel.github.io；
    b. 增加TXT记录：主机记录_github-pages-challenge-larksquirrel.ryanrochad.com，记录值d8230e127be255ae508193d3c6ed30。
        !!!注意：用新的github账户生成链接时，需要先verify该账户（不是仓库是账户）：Settings—Pages—Add a domain，输入ryanrochad.com，生成TXT记录添加到DSN中。
3. 检验DSN是否更新完成：
    a. 检验网址：https://dnschecker.org/#A/_github-pages-challenge-ryanrochad.www.ryanrochad.com
    b. 左侧框内填写：_github-pages-challenge-ryanrochad.www.ryanrochad.com

2025/08/20
1. 更新代码：
    a. 增加各页面跳转逻辑（Service除外）。

2025/08/22
1. 讨论新增功能：
    a. 云端地球：https://www.get3d.cn/culturaHeritageDataSpace
       自主3D建模

2025/11/01
1. 更新代码：
    a. 增加dl.html的切换及注册sign up功能界面
    b. 将ziliao.html加入主体，分栏名为Account，登录后的跳转界面
2. 建立Supabase数据库
    a. github账户，密码：01231003heihua
3. 暂时不能实现的：
    a. QQ和微信的登录，需要备案

2025/11/02
1. 更新代码：
    a. ziliao.html增加动态显示用户信息功能及更改密码功能
    b. ziliao.html删除了显示密码功能（Supabase隐私保护不允许）
    c. ziliao.html更改了分栏跳转内容，并增加删除链接蓝色下划线的style样式
    d. 统一大小写等样式问题
2. Supabase数据库配置
    a. 更改注册Email内容为RR专属内容（由其他同事提供文案）


