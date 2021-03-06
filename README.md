# 大一学习《C语言程序设计》后写的新冠疫情数据管理系统课程设计。 (实现所有功能)

> &emsp;&emsp;&emsp;针对当前疫情开发一个新冠疫情数据管理系统。主要用来统计，管理并展示新冠疫情相关数据，数据包括两大部分，一部分为全国数据，包括：*累计确诊，新增确诊，累计治愈，新增治愈，累计死亡，新增死亡，现有疑似，疑变化（新增或减少），现有重症，重症变化（新增或减少）。* 另一部分为各省区市数据，同时作为全国数据的基础数据，包括：*累计确诊，新增确诊，累计治愈，新增治愈，累计死亡，新增死亡，现有疑似，疑似变化（新增或减少），现有重症，重症变化（新增或减少）。* 上述数据均须存储在文件中。  
> &emsp;&emsp;&emsp;系统的使用者角色分为两类：一类为管理员（或称录入员），负责录入各省新增数据，完成对全国数据的更新，数据每天更新一次，并且可以修改某日某省的某项数据。另一类为普通用户，可以查询各省的全部数据，可以查询全国的全部数据，可以以累计确诊数为基准降序查看所有省份的累计确诊，累计治愈和累计死亡数据。可以查看是否存在数据拐点，若存在，可查看出现拐点的日期（拐点日期的特征：该日的全国新增确诊数高于前五日，且与其后五日的全国新增确诊数呈递减序列）。可以查询任意日期段内的全国各项平均数据。管理员与普通用户拥有不同菜单界面。  
> 备注：  
> 1.累计确诊，累计治愈，累计死亡，现有疑似和现有重症数据之间相互独立，无联系。  
> 2.可先利用程序或手动输入各省基础数据，存入文件中。在后续输入模拟的每日新增数据时，可酌情录入某些省份的新增数据，其余省份默认为0。以减少调试工作量。本系统的适用日期从2020年1月1日至5月1日。  
> 3.有兴趣同学可完成提高要求：针对管理员可设计用户名密码登录界面；增加城市级别数据；实现非图形化界面的各项数据曲线图展示（使用字符等方式展示曲线图）。  
