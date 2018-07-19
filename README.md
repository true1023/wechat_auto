# wechat_auto

## Function list

1. weather.py 定时获取当天所有天气的预报数据，保存到本地，之后通过调用则返回本地数据
2. 控制台完成
3. 问候接口完成，可以动态设置时间
4. 根据系统提示存储已删好友信息，定期清理好友列表
5. 自动通过好友请求，打招呼并提醒关注公众号
6. 默认打乱好友列表，定时消息只给有限数量的人发送，数量保存在MAX_COUNT全局变量，默认是100

## Specification

根目录下必须有storage文件夹用来存放数据，
storage文件夹下须有city.json文件告诉组件需要提前请求哪些城市的天气情况
具体格式参考github上的模板

# New features
如果好友的备注是“例外”那么无论如何都不会自动AI回复

# Bug Fixed
改变了userid的获取方式，不会在调用图灵AI时出现userid错误的问题