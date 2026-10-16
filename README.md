# 全开源餐饮在线点餐系统小程序源码搭建（ThinkPHP+Uniapp）
 获取源码：ym7k.com/17837/
一、主流开源方案

三勾点餐系统：基于 ThinkPHP8 + Element Plus + UniApp，多端发布（微信小程序、H5、App），支持 SAAS 多店模式，Gitee 开源地址：https://gitee.com/victor123/jjjfood，有免费版和付费版。
点大餐饮独立版：ThinPHP + UniApp 前端，支持全渠道点餐、智能收银、多门店管理，含 20+ 营销插件，版本 v1.0.3，附带搭建教程。
其他全开源套装：多采用 ThinkPHP + FastAdmin + UniApp 组合，类似肯德基/喜茶风格的多店铺模式，支持子商户、扫码点餐、外卖配送、积分商城、优惠券、二级分销、云打印等完整功能，提供全部前后台无加密源代码和数据库。
二、基本功能覆盖

堂食点餐：扫码桌码点餐、排队叫号；外卖带走：下单后自取或配送。
支付结算：微信支付，支持先付后吃和先吃后付两种模式。
商家端：多门店独立管理、菜品/订单/财务数据汇总、店员角色权限。
营销工具：优惠券、满减、积分商城、钱包储值、二级分销。
三、搭建步骤（整体流程）

准备服务器环境：PHP 8.0+、MySQL 8.0、Redis 7.0、Nginx，搭配宝塔面板快速配置。
下载源码部署到服务器，创建数据库并导入 SQL 初始化脚本。
配置后端环境：修改数据库连接、JWT 密钥、微信支付参数与回调地址。
前端用 HBuilder X 打开 UniApp 工程，修改接口域名后编译发布到微信小程序。
配置微信支付商户号、小程序密钥，提交微信审核，通过后上线。
<img width="1024" height="988" alt="2025070419032222" src="https://github.com/user-attachments/assets/3a969070-abb8-4a89-8dbb-86fd46ae2651" />
<img width="1018" height="1024" alt="2025070419034046" src="https://github.com/user-attachments/assets/3a37e83e-5f44-4975-8690-e90ef5fda544" />
