# f2e新手指引
欢迎来到f2e大家庭
## 关于svn

我们使用TortoiseSVN工具
## svn地址目录
 1. svn://61.135.254.16/go/ (常规专题)
 2. svn://61.135.254.16/auto/ (汽车专题)
## 创建svn时的注意事项
 - 创建目录时, 按照/年份/日期/ 创建, 例如svn://61.135.254.16/auto/2016/0731/toyota-wap
 - 专题地址创建的时候,日期写成上线日期
 - 创建活动链接时, 先问执行链接后缀有无特殊要求, 没有再创建, 一般手机端页面后缀写上"-wap"
 - 不要用svn上传视频文件到服务器 (需要找任科帮忙上传)
 - 涉及到后台功能, 让执行直接找后台沟通
 - 在复制专题文件夹的时候不要把php文件一起复制过去
 - 更加快速的同步到正式服务器的方法: 因为服务器会有缓存, 当修改完成后, 先提交svn, 再在html加版本号
 - 生成的测试链接地址为:
   * http://test.go.163.com/go/年份/日期/项目名称 (常规专题)
   * http://test.go.163.com/auto/年份/日期/项目名称 (汽车专题)
 - 生成的正是链接地址为:
   * http://go.163.com/年份/日期/项目名称/ (常规专题)
   * http://s.auto.163.com/年份/日期/项目名称/ (汽车专题)
