# Fastadmin-plugin-arife

#### 介绍

个人开发整合fastadmin常用插件集合

###### addonmask  官网插件屏蔽

###### alidayu  阿里云短信

###### feedback 意见反馈(带接口)

###### geo 省市区街道四级联动

###### invite-regular 会员邀请好友

###### news 新闻资讯_1

###### notice 发布平台公告(有详情)

###### sysmessage 发布平台消息(无详情)

###### cms CMS内容管理系统(含小程序)

###### channel 用户营销渠道

###### comments 文章评论管理

###### document 文档管理(如协议,简介)

###### facrm-2.0.6-extended CRM客户关系管理系统

###### wwh-1.2.0-regular 企业官网

###### shop-1.1.0 移动端商城(基础功能设置)

###### shopro-1.3.8-basicr Shopro商城-移动端商城,分销(高级授权),店铺装修,直播,拼团,数据统计,客服,门店核销

#### 安装教程

1. 修改config.php文件:
   `'unknownsources' => true,
   'app_debug' => Env::get('app.debug', true),
   'app_trace' => Env::get('app.trace', true),`

2. 找到/vendor/karsonzhang/fastadmin-addons/src/addons下的service.php文件的200行，注释掉，保存即可。

3. 框架版本>=1.2的

#### 使用说明

1. 开箱即用, 如须修改请直接修改插件相关控制器或视图文件
2. 如果需要升级后打包, 请参考官方插件开发文档, 整理好文件目录结构后进行重新打包
3. 部分插件(最后放上的)没有进行单独安装测试, 但文件没丢失应该不会有问题, 须自行测试

#### 杂项

1. 新开发插件名称重复官方检测地址: https://www.fastadmin.net/developer/idcheck.htm
2. 部分插件安装时, 即使`unknownsources=>true`, 也会提示"请从插件市场下载..", 是因为插件名与官方市场插件名称冲突,
   此时可安装addonmask插件先临时屏蔽, 安装完成之后请及时禁用该插件(addonmask)

