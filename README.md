#永远辞职#

在你的职业生涯中，也许会有这样的经历:曾经一起奋斗的合伙人陡然而富，成为公司的老板，而你却越来越
像个打工仔，一走了之却只能显得你是如此的苍白无力; 老板们每天给你画大饼，然而
却连三个月前的工资都发不出来，想要一走了之，却又不甘心受了欺负。你抱着深深的怨念想要永远
的 离开程序猿这个工种，一去不会,想要一走了之，却又想留下点什么。

**那么**
```bash
  ./resign-forever &
```
这个脚本就可能会满足你的需求，放在你们公司ssh链接最多的服务器上，在你搬着自己的东西走人之前
后台运行一下，然后转身离去，真男人从不回头看爆炸！

哈哈 脚本很简单，原理大家一看就明白，如果有什么方法能够屏蔽掉这个脚本的运行，那么请以在issue中
提交BUG的方式告诉我。我会尽快升级脚本。

现在脚本只对Red Hat类似的伪终端实现方式有效，没有接触过BSD的主机，所以也没法开发对应版本哈。

至于这个脚本的效果嘛，就是对当前主机的所有ssh连接过来的用户（包括运行时就存在的及运行中连接上来的）
进行持续的，频繁的发送 F*UCKU 图案，草鸡爽。

慎用！慎用！慎用！ 重要的事说三遍 ———— 《德》尼采
