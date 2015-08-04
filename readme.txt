Git is a distributed version control system.
Git is free software distributed under the GPL.

newmessage is added.
newly added message

git log

Git has a mutable index called stage.
         MT4CTP软件 期货品种 设置打开或关闭 操作步骤

删除MT4行情图表的EA，关闭MT4软件。

系统设置期货品种IF1503换到IF1504.
找到文件SymbolsCTP.csv位置
 
 
双击打开：注意最后一列，1是打开期货品种行情，0是关闭期货行情。设置好保存。
修改前：
 
修改后：
 

TB导入数据
打开图表，加载需要的期货代码，依次切换到各个时间周期刷新数据（例如：日，60，30，5，1分钟）。每个时间周期停留一会，确保下载了最新数据。
 
进入菜单：数据管理，
数据维护  选择交易所—商品---周期  导出。确认是今天最新数据。2015年3月20日星期五
导出数据 
 

  
数据放在这里。导出所有数据开始转换格式。
 

 

生成代码，刷新代码
打开转换工具
打开 
 
添加分组，显示分组内容，确认你的期货代码是否打开或者关闭。
点击-生成MT4代码
再点击5刷新symbls.sel
 

导入数据：
 
