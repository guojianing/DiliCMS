﻿# DiliCMS 

欢迎使用DiliCMS,DiliCMS是无业务逻辑的，面向CodeIgniter开发者的自由灵活的系统，致力于为开发者提供最简单，灵活，实用的后台CMS系统。

## 安装方法

- 普通平台
```
1.新建数据库，并导入db.sql
2.配置application和admin文件夹下的/config/database.php,配置表前缀为dili_
3.运行http://your-url/admin/index.php/initialize,初始化系统
4.欢迎来到DiliCMS的世界
```

- SAE平台
```
1.使用SAE平台的phpmyadmin导入db.sql
2.配置application和admin文件夹下的/config/database.php,,配置表前缀为dili_
3.配置shared/config/platform.php为
    $running_platform = array(
        'type'		=> 'sae',//修改default为sae.
		'storage'   => ''//这里填写你在SAE上storage的domain名称.
	);
4.运行http://your-url/admin/index.php/initialize,初始化系统
5.欢迎来到DiliCMS的世界

```

> ### 默认帐号为：admin,密码为:dilicms

## 更新日志
    
    点击CHANGELOG.md查看
    
## LICENSE
Copyright (c) 2013 [DiliCMS](http://www.dilicms.com).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
