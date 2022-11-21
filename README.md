# hifini-signin
HIFINI音乐磁场自动签到

# 使用方式
1. 新建仓库并同步代码
2. 点击Settings -> Secrets -> 点击绿色按钮 (如无绿色按钮说明已激活。直接到下一步。)
3. 新增 new secret 并设置Secrets
4. 双击右上角自己仓库Star触发
6. **必须** - 请随便找个文件(例如`README.md`)，加个空格提交一下，否则可能会出现无法定时执行的问题
7. 由于规则更新,同步后会默认禁用,请手动点击Actions 选择要签到的项目 `enable workflows`激活
8. [定时执行](#定时执行) (如修改了执行时间 请关闭同步源仓库  否则同步时会覆盖)
# COOIKIE添加格式
| 名称               | 内容                      | 说明                                                                                                                 |
|------------------|-------------------------|--------------------------------------------------------------------------------------------------------------------|
| `COOKIE`            | [HIFINI网站](www.hifini.com)COOKIE | F12控制台执行`console.log(document.cookie)`                                                                     |



# 定时执行
1. 支持手动执行，具体在Actions中选中要执行的Workflows后再在右侧可以看到Run workflow，点击即可运行此workflow。

2. 如果嫌上一步麻烦的，也可以直接点击一下自己的star，你会发现所有的workflow都已执行。

3. 如需修改执行时间自行修改`.github\workflows\`下面的yaml内的` cron:` 执行时间为国际标准时间 [时间转换](http://www.timebie.com/cn/universalbeijing.php) 分钟在前 小时在后 尽量提前几分钟,因为安装部署环境需要一定时间 
     
     
     
          
