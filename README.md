//小白配置
//导入之后--生成证书--配置证书--信任证书--引用你的机场订阅（开启资源解析器）即可。


[general]
//通用参数设置
excluded_routes=192.168.0.0/16, 172.16.0.0/12, 100.64.0.0/10, 10.0.0.0/8, 127.0.0.0/8, 224.0.0.0/24
geo_location_checker=http://ip-api.com/json/?lang=zh-CN, https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/IP_API.js
resource_parser_url= https://cdn.jsdelivr.net/gh/KOP-XIAO/QuantumultX@master/Scripts/resource-parser.js
network_check_url=http://cp.cloudflare.com/generate_204
server_check_url=http://www.gstatic.com/generate_204

[dns]
no-ipv6
no-system
server=1.2.4.8
server=223.5.5.5
server=119.28.28.28
server=119.29.29.29
server=114.114.114.114 
server=119.29.29.29:53
server=/*.163.com/119.29.29.29
server=/*.126.com/119.29.29.29
server=/*.126.net/119.29.29.29
server=/*.127.net/119.29.29.29
server=/*.taobao.com/223.5.5.5
server=/*.tmall.com/223.5.5.5
server=/*.alipay.com/223.5.5.5
server=/*.alicdn.com/223.5.5.5
server=/*.aliyun.com/223.5.5.5
server=/*.jd.com/119.28.28.28
server=/*.qq.com/119.28.28.28
server=/*.tencent.com/119.28.28.28
server=/*.weixin.com/119.28.28.28
server=/*.bilibili.com/119.29.29.29
server=/hdslb.com/119.29.29.29
server=/*.163.com/119.29.29.29
server=/*.126.com/119.29.29.29
server=/*.126.net/119.29.29.29
server=/*.127.net/119.29.29.29
server=/*.netease.com/119.29.29.29
server=/*.mi.com/119.29.29.29
server=/*.xiaomi.com/119.29.29.29
address=/mtalk.google.com/108.177.125.188

[server_remote]
https://paste.in/raw/gERwIk, tag=123456, update-interval=172800, opt-parser=true, enabled=false
https://link.jscdn.cn/1drv/aHR0cHM6Ly8xZHJ2Lm1zL3QvcyFBdW9feDR6U1kwXzZoX05IeVhYTG9EVl8zQnlkbkE_ZT00QVNYcDI, tag=白嫖的, update-interval=172800, opt-parser=true, enabled=false
2E075F289769.snippet, tag=红杏出墙, update-interval=172800, opt-parser=false, enabled=true
//远程机场订阅加这里
//https://raw.githubusercontent.com/crossutility/Quantumult-X/master/server.txt#rename=[香港], tag=示范(请先导入自己订阅/节点), update-interval=86400, opt-parser=true,  img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Quantumult_X.png, enabled=true


[server_local]


//本地节点填这里


[task_local]
//js脚本定时任务加这里
5 0 * * * https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js, tag=京东, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/JD_DailyBonus.png, enabled=true
1 0 * * * https://raw.githubusercontent.com/chavyleung/scripts/master/tieba/tieba.js, tag=百度签到, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/tieba.png, enabled=true
0 1,18 * * * https://raw.githubusercontent.com/whyour/hundun/master/quanx/jx_factory_component.js, tag=京喜工厂plus, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jx_factory_component.png, enabled=true
11 1 * * * https://raw.githubusercontent.com/yangtingxiao/QuantumultX/master/scripts/jd/jd_lotteryMachine.js, tag=抽奖机, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_lotteryMachine.png, enabled=true
10 7 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_ms.js, tag=京东秒秒币, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_ms.png, enabled=true
15 19 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/backUp/xmSports.js, tag=小米运动, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/xmSports.png, enabled=true
20 13 * * 6 https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_get_share_code.js, tag=获取互助码, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_get_share_code.png, enabled=true
20 0-23/3 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_jxmc.js, tag=京喜牧场, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_jxmc.png, enabled=true
20 * * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_big_winner.js, tag=省钱大赢家之翻翻乐, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_big_winner.png, enabled=true
4 10 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_jxlhb.js, tag=京喜领88元红包, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_jxlhb.png, enabled=true
13 1,22 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_gold_creator.js, tag=金榜创造营, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_gold_creator.png, enabled=true
10 * * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_jin_tie.js, tag=领金贴, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_jin_tie.png, enabled=true
4 10 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_market_lottery.js, tag=幸运大转盘, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_market_lottery.png, enabled=true
5-45/20 * * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_health_collect.js, tag=东东健康社区收集能量, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_health_collect.png, enabled=true
10 0,23 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_health.js, tag=东东健康社区, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_health.png, enabled=true
0 2 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_cash.js, tag=签到领现金, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_cash.png, enabled=true
1 8,12,18 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_bookshop.js, tag=口袋书店, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_bookshop.png, enabled=true
10 7 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_crazy_joy.js, tag=CrazyJoy任务, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_crazy_joy.png, enabled=true
12 * * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_pigPet.js, tag=京东金融-养猪猪, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_pigPet.png, enabled=true
0 */3 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_daily_egg.js, tag=京东金融-天天提鹅, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_daily_egg.png, enabled=true
10 0 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_kd.js, tag=京东快递签到, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_kd.png, enabled=true
0 0 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_car_exchange.js, tag=京东汽车兑换, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_car_exchange.png, enabled=true
10 7 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_car.js, tag=京东汽车, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_car.png, enabled=true
10 7 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_bean_home.js, tag=领京豆额外奖励, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_bean_home.png, enabled=true
10 7 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_syj.js, tag=赚京豆, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_syj.png, enabled=true
10 0,20 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_necklace.js, tag=点点券, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_necklace.png, enabled=true
10 * * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_jdfactory.js, tag=东东工厂, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_jdfactory.png, enabled=true
16 0 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_small_home.js, tag=东东小窝, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_small_home.png, enabled=true
10 * * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_dreamFactory.js, tag=京喜工厂, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_dreamFactory.png, enabled=true
2 9 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_bean_change.js, tag=京豆变动通知, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_bean_change.png, enabled=true
0 0 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_jdzz.js, tag=京东赚赚, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_jdzz.png, enabled=true
1 1 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_redPacket.js, tag=京东全民开红包, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_redPacket.png, enabled=true
5 0 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_club_lottery.js, tag=摇京豆, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_club_lottery.png, enabled=true
10 0 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_shop.js, tag=进店领豆, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_shop.png, enabled=true
0 0 0 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_blueCoin.js, tag=京小超兑换奖品, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_blueCoin.png, enabled=true
11 1-23/5 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_superMarket.js, tag=东东超市, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_superMarket.png, enabled=true
3 */2 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_moneyTree.js, tag=摇钱树, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_moneyTree.png, enabled=true
8 */3 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_speed.js, tag=天天加速, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_speed.png, enabled=true
1 7-21/2 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_plantBean.js, tag=种豆得豆, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_plantBean.png, enabled=true
15 6-18/6 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_pet.js, tag=东东萌宠, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_pet.png, enabled=true
5 6-18/6 * * * https://raw.githubusercontent.com/ChuheGit/1/main/Script/jd_scripts/jd_fruit.js, tag=东东农场, img-url=https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/jd_fruit.png, enabled=true

event-interaction https://raw.githubusercontent.com/I-am-R-E/QuantumultX/main/TaskLocal/NeteaseMusicUnlockCheck.js, tag=网易音乐查询, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netease_Music_Unlock.png, enabled=true
event-interaction https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/streaming-ui-check.js, tag=流媒体-解锁查询, img-url=checkmark.seal.system, enabled=true


[policy]
//策略组加这里
static=Spotify, server-tag-regex=.*, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Spotify.png
static=Telegram, direct, proxy, reject, 延迟最低, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Telegram.png
static=Apple服务, direct, 节点选择, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Apple_1.png
static=Netflix, resource-tag-regex=.*, server-tag-regex=.*, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netflix.png
static=广告拦截, reject, direct, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Adblock.png
static=BiliBili, direct, proxy, reject, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/bilibili.png
static=节点选择, direct, proxy, 手动选择, 延迟最低, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Luffy.png
static=手动选择, server-tag-regex=🇭🇰, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Clubhouse.png
url-latency-benchmark=延迟最低, server-tag-regex=洛, check-interval=150, tolerance=10, alive-checking=false, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/Urltest.png
static=网易云音乐, direct, proxy, 手动选择, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Netease_Music_Unlock.png
static=TikTok, 延迟最低, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/TikTok.png

[filter_remote]
//分流规则填这里
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/ChinaIP.list, tag=国内ip池, force-policy=Apple服务, update-interval=172800, opt-parser=true, enabled=false
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/StreamingCN.list, tag=国内视频, force-policy=Apple服务, update-interval=172800, opt-parser=true, enabled=false
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/AdvertisingLite/AdvertisingLite.list, tag=AdvertisingLite, force-policy=广告拦截, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/QuantumultX/Spotify/Spotify.list, tag=Spotify, force-policy=Apple服务, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/QuantumultX/BiliBili/BiliBili.list, tag=哔哩哔哩, force-policy=BiliBili, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/QuantumultX/Telegram/Telegram.list, tag=TG分流, force-policy=Telegram, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Global.list, tag=国外网站, force-policy=延迟最低, update-interval=86400, opt-parser=true, enabled=false
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/Streaming.list, tag=国际视频, force-policy=延迟最低, update-interval=86400, opt-parser=true, enabled=false
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/AppStore.list, tag=AppStore, force-policy=Apple服务, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/shunt/Netease.list, tag=网易云音乐, force-policy=网易云音乐, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/AppStoreConnect.list, tag=AppStoreConnect, force-policy=Apple服务, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Apple/TestFlight.list, tag=Testflight, force-policy=Apple服务, update-interval=86400, opt-parser=true, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/Video/Netflix.list, tag=Netflix, force-policy=Netflix, update-interval=86400, opt-parser=true, enabled=true
[rewrite_remote]
https://raw.githubusercontent.com/VirgilClyne/iRingo/main/qxrewrite/Location_Services.beta.qxrewrite, tag=测试的, update-interval=172800, opt-parser=true, enabled=false
https://raw.githubusercontent.com/VirgilClyne/iRingo/main/qxrewrite/Geo_Services.qxrewrite, tag=Apple Gps, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/JS_GetCookie.conf, tag=Cookie, update-interval=43200, opt-parser=true, enabled=false
https://raw.githubusercontent.com/app2smile/rules/master/module/spotify.conf, tag=Spotify Root, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/TikTok.conf, tag=Tiktok, update-interval=172800, opt-parser=true, enabled=false
https://service.2ti.st/QuanX/Rewrite/jd_tb_price.conf, tag=比价脚本, update-interval=172800, opt-parser=true, enabled=false
https://raw.githubusercontent.com/Semporia/TikTok-Unlock/master/Quantumult%20X/TikTok-TW.conf, tag=Tiktok TW, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/VirgilClyne/iRingo/main/qxrewrite/Siri.qxrewrite, tag=Apple Siri, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/VirgilClyne/iRingo/main/qxrewrite/Weather.qxrewrite, tag=Apple Weather, update-interval=172800, opt-parser=true, enabled=true
//远程重写复写填这里
https://raw.githubusercontent.com/id77/QuantumultX/master/rewrite/Youtube_CC.conf, tag=Youtube 翻译, update-interval=172800, opt-parser=true, enabled=true
https://raw.githubusercontent.com/jh2921291/QuantumultX/master/YouTube.conf, tag=YouTube去广告, update-interval=172800, opt-parser=true, enabled=true

[filter_local]
//本地分流规则填这里

host, p62-keyvalueservice.icloud.com.cn, proxy
host, pagead2.googlesyndication.com, proxy
ip-cidr, 47.97.17.20/24, direct
host, 18comic.vip, proxy
host, ocsp.apple.com, reject
host-suffix, local, direct
ip-cidr, 10.0.0.0/8, direct
ip-cidr, 127.0.0.0/8, direct
ip-cidr, 172.16.0.0/12, direct
ip-cidr, 192.168.0.0/16, direct
ip-cidr, 224.0.0.0/24, direct
host, pgdt.gtimg.cn, reject
host, myqcloud.com, reject
geoip, cn, direct
final, 延迟最低

[rewrite_local]

//本地重写填这里



[mitm]
;以下模块去掉;才生效
;请自行在 APP 的UI中生成证书 并安装&信任
;skip_validating_cert = false
;force_sni_domain_name = false
passphrase = DBB44633
p12 = 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
hostname = *., qjp.qujianpan.com, equities.sunwaystech.com, mspace.gmmc.com.cn, *.xiaodouzhuan.cn, plus.dutenews.com, proxy.guodongbaohe.com, *.tenpay.com, springglasses.com, speedcy.springglasses.com, wq.jd.com, un.m.jd.com, api.m.jd.com, api1.ktvcggl.com, b2b.homedo.com, -*snssdk.com, -*amemv.com, redbag.renyouwangluo.cn, api-access.pangolin-sdk-toutiao.com, znapi.yili.com, minigame.ucpopo.com, -*.snssdk.com, -*.amemv.com, mi.gdt.qq.com, vip.75787.com, sdk.121827.com, jk.5apk.cn, ddstar.palmmob.com, yuedongzu.yichengw.cn, huodong.fanli.com, passport.fanli.com, gw.fanli.com, *.youth.cn, ios.baertt.com, veishop.iboxpay.com, e.189.cn, .*.top, *.pceggs.com, www.ipadview.com, *.reader.yueyouxs.com, m.*, cat.rxmao.net, node.52tt.com, api-9f9d25.sz365.cn, jqb.iphonezhuan.com, account.huami.com, dkd-api.dysdk.com, api.sxsjyzm.com, api.rsxsjyzm.com, api.hemayoudao.cn, ymz.iphonezhuan.com, *.bilibili.com, music.163.com, act.10010.com, m.client.10010.com, iface?.iqiyi.com, nebula.kuaishou.com, trade-acs.m.taobao.com, mp.weixin.qq.com, *.amemv.com, ms.jr.jd.com, wapside.189.cn, wx.10086.cn, draw.jdfcloud.com, jdjoy.jd.com, www.52pojie.cn, api.shatuvip.com, api.weibo.cn, bp-api.coohua.com


[http_backend]
https://raw.githubusercontent.com/chavyleung/scripts/master/chavy.box.js, tag=Boxjs, path=^/, enabled=true
