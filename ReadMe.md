## 起因
老婆从事的是售后的工作，常年需要把售前工程师和销售的一些实施的数据录入到他们的工作平台上。

最开始我看在眼里，焦虑在心上，我心想，你这完全是人力无价值的搬运工的(excel到网页表单)工作，你们公司难道不能把录入这一部分的工作开放给更前线的人或者提供一个excel导入的工具吗？老婆摇摇头说，这个事已经提了n年了，以她这工作岗位在公司里的重要程度，还不足以让开发工程师紧着她做事，他们还有“更重要的事”要做。

曾几何时，开发出身的我也想着让她学学Js,Python什么的，可是对于她来说，学写程序和看剧这两件事情无疑看剧是```更重要的事```。

为了拯救老婆的双眼和布道计算机就是生产力，我抽起了老刀，咔咔咔，不辱使命。

-----


[不愿意用github的懒人看这里，收点税 V0.0.5](https://download.csdn.net/download/flyback/12316927)

[操作说明](https://jingyan.baidu.com/article/b7001fe14ed9bf4f7382dd33.html)

[github源代码](https://github.com/kjflyback/excelimportor/tree/kjflyback-nomovie)

*已知问题*
- 使用的excel文件需要把末尾的空列全部删除，否则会出现不能弹出数据匹配窗口,以及CPU使用率偏高的问题
- 在打开chrome的整个运行期间,调试控制台会出现runtime error的日志，这个```不影响使用```
- 最好把别的扩展关掉，避免可能存在的影响
-----
V0.0.8

V0.0.7
- [X] 加入对checkbox控件的支持
- [X] 修改数据匹配窗口显示方式为紧贴网页的顶部
- [X] 修改数据匹配窗口的对应列当超过Z时显示为n列
 
V0.0.6
- [X] 加入对radio控件的支持

V0.0.5
- [X] 修改了操作方式




