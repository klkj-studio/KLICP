# 开朗ICP

开朗ICP是一款基于PHP构建的虚拟ICP备案查询系统，旨在帮助用户快速搭建ICP备案查询功能。

本项目由ChatGPT进行润色。

[演示站点](https://icp.kldhsh.top/)

## 功能介绍

- 查询ICP备案信息
- 后台管理和审核
- 数据提交基本安全
- 验证码部分（未实现）
- 后台密码（未实现）

## 使用方法

1. 将本仓库克隆到您的服务器上。

2. 在服务器上安装PHP环境。

3. 在服务器上安装MySQL数据库，并创建一个数据库。

4. 在数据库中导入项目根目录提供的数据表。

5. 编辑根目录的 `db_connection.php` 文件，将数据库连接信息修改为您自己的数据库信息。

6. 进入目录 `./site/admin/ver`，修改 `approve.php` 和 `delete.php` 的SMTP部分。

7. 修改`./text.php文件的站点地址`

8. 修改站点信息以实现自定义。

9. 设置运行目录`site`

10. 在浏览器中访问您的站点，即可使用开朗ICP备案查询。

后台地址为 `./admin`。

## 注意事项

1. 本项目仅供学习和研究使用，请勿用于非法用途。
2. 项目使用Apache 2.0开源协议，请在您的二次开发项目中加上本仓库的地址并标明开发者。
3. 后台加密未实现，您可能需要采用类似"宝塔访问限制"的功能来保护后台访问安全。

