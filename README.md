# WalkingTec.Mvvm for aspnet core

WalkingTec.Mvvm框架（简称WTM）最早开发与2013年，基于Asp.net MVC3 和 最早的Entity Framework, 当初主要是为了解决公司内部开发效率低，代码风格不统一的问题。经历了四年间数十个项目的考验，框架逐步的完善，推出了四个主要版本。 2017年9月，我们将代码移植到了.Net Core上，并进行了深度优化和重构，推出了基于Asp.net Core和EF Core的全新框架，新框架在架构，稳定性，速度上都有长足进步，真正成为一款高效开发的利器。

正式版：
[![Build status](https://dev.azure.com/vitowu/WTM/_apis/build/status/WTM-CI-master-nuget.org)](https://dev.azure.com/vitowu/WTM/_build/latest?definitionId=4)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdotnetcore%2FWTM.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdotnetcore%2FWTM?ref=badge_shield)

测试版：
[![Build status](https://dev.azure.com/vitowu/WTM/_apis/build/status/WTM-CI-develop-nuget.sundot)](https://dev.azure.com/vitowu/WTM/_build/latest?definitionId=3)

Package name                              | Stable (master branch)
-------------------------------------------|-----------------------------
`WalkingTec.Mvvm.Core` | [![NuGet](https://img.shields.io/nuget/v/WalkingTec.Mvvm.Core.svg?style=flat-square&label=nuget)](https://www.nuget.org/packages/WalkingTec.Mvvm.Core/)
`WalkingTec.Mvvm.Mvc` | [![NuGet](https://img.shields.io/nuget/v/WalkingTec.Mvvm.Mvc.svg?style=flat-square&label=nuget)](https://www.nuget.org/packages/WalkingTec.Mvvm.Mvc/)
`WalkingTec.Mvvm.Mvc.Admin` | [![NuGet](https://img.shields.io/nuget/v/WalkingTec.Mvvm.Mvc.Admin.svg?style=flat-square&label=nuget)](https://www.nuget.org/packages/WalkingTec.Mvvm.Mvc.Admin/)
`WalkingTec.Mvvm.TagHelpers.LayUI` | [![NuGet](https://img.shields.io/nuget/v/WalkingTec.Mvvm.TagHelpers.LayUI.svg?style=flat-square&label=nuget)](https://www.nuget.org/packages/WalkingTec.Mvvm.TagHelpers.LayUI/)

框架主要特点：

框架提供了4类ViewModel，涵盖了主流Web应用程序常见的功能，分别是： 
  BaseCRUDVM 提供最常见的数据增删改的功能
  PagedListVM 提供分页列表以及导出的功能
  ImportVM & TemplateVM 提供数据导入的功能
  BatchVM 提供批量操作的功能

框架自带代码生成器，开发高效快捷

框架提供了数十种前台控件，包括了Form,Grid,Panel,Dialog等几乎所有常用控件，在不进行前后分离的情况下，后端人员也可以轻松写出漂亮的前台页面。目前框架只支持Layui作为前端UI，后期我们会支持更多。 

框架提供了内置的用户，角色，用户组，数据权限，页面权限，菜单，日志，邮件，短信，文件等后台常用管理功能 

框架支持单点登录，门户Portal，分布式数据库 

框架提供了Redis,DFS等后台开发常用库的简化操作 


在言必谈Java微服务的今天，在不论项目规模，不管项目类型，不计成本，疯狂前后端分离的今天，WTM框架无疑是一股清流。（当然，WTM框架也支持编写服务。。。）

从2.2.8开始，WTM框架开始支持前后端分离的模式，目前还是预览版，前端只支持react，欢迎大家提出宝贵意见。WTM框架的前后端分离模式极大的降低了前后端人员的沟通成本，从本质上提升了开发效率，让“分离”不再复杂和昂贵。

框架文档地址：http://wtmdoc.walkingtec.cn  文档还在不断完善中。。。
框架QQ交流群：694148336

您可以点这里 http://wtmdoc.walkingtec.cn/setup 在线一键生成WTM的项目，立刻开始体验WTM之美~~~


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdotnetcore%2FWTM.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdotnetcore%2FWTM?ref=badge_large)