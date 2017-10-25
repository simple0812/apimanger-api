# 云笔记接口端

## 帐号

1. **注册** 需要输入`邮箱`和`密码`，系统发送激活信息，帐号需要激活才能登录使用。
1. **登录** 密码当天连续`3次`错误锁定帐号，需要通过邮箱找回密码。
1. 密码长度必须大于6位。
1. 用户名称默认使用邮箱`@`符号前面的代替。
1. 头像随机一个默认头像。

## 分组

1. 系统初始化有一个默认分组 `我的分组`。
1. 分组有层级关系，相同层级分组名称不能相同。
1. 分组名称不能为空。
1. 一个分组对应多个笔记，一个笔记对应一个分组。

## 标签

1. 标签名称不能重复且不能为空。
1. 标签和笔记是多对多关系。

## 笔记

1. 标题不能为空。
1. 内容采用 `markdown` 书写。
1. 内容对应一个分组。
1. 内容可以有多个标签。
1. 笔记可设置分享，分享可以设置密码。

## 任务列表

- [x] 注册
- [x] 激活帐号
- [x] 登录
- [x] 找回密码
- [ ] 密码错误次数过多锁定帐号
- [ ] 修改个人信息
- [ ] 修改密码
- [x] 获取分组
- [x] 添加分组
- [ ] 修改分组
- [x] 删除分组
- [x] 获取标签
- [x] 添加笔记
- [x] 修改笔记
- [x] 删除笔记
- [x] 公开分享笔记
- [ ] 私有分享笔记