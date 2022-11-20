# quarkus-admin

基于Quarkus的现代化的、云原生的企业开发基础架构。

使用到的相关框架：

> * 后端：[云原生Java框架 Quarkus ](https://quarkus.io/)
> * 前端：[Ant-Design-pro](https://pro.ant.design/)

## 开发快速启动

> mvn quarkus:dev

 请先安装docker，框架将自动下载并启动依赖的Postgre数据库并完成数据初始化。（如需使用Mysql，替换POM中的数据库Client依赖即可）

## Quarkus-Admin 功能列表

- 1.组织管理
- 2.用户管理
- 3.权限管理
- 4.角色管理
- 5.菜单管理

## 技术选型

### 后端技术

| 技术        | 类型     | 
| --------   | ------   |
| Quarkus    | 框架      |
| RESTEasy   | web      |
| Hibernate  | ORM      |
| Hibernate Validator   |   校验框架  |
| Mutiny     | 响应式编程 |
| RESTEasy   | web      |
| JWT        | 权限      |
| Kogito     | 工作流    |


### 前端技术

| 技术                   | 类型     | 
| --------              | ------   |
| React                 | JS框架    |
| Ant-Design-Pro        | UI框架    |

## Todo 列表

- [ ] 支持 权限控制
    - [ ] 支持 JWT RBAC 权限
- [ ] 支持 自动化/工作流
