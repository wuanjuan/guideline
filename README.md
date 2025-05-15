## 代码托管使用手册


### 新用户注册
- 如果新用户尚未拥有 GitHub 账号，请访问 [GitHub 注册页面](https://github.com/signup) 创建账号。
- 注册完成后，请将 GitHub 账号信息发送给管理员（钉钉：13819899375）。

### 代码仓库创建
- 创建新的代码仓库时，请选择 **private** 类型。
- 代码仓库名称应全部使用小写字母，并遵循以下命名规范：`<client_name>-<project_name>-<code_function>`。
    - `client_name`: 客户名称，例如人才集团 (talentgroup)。
    - `project_name`: 项目名称，例如人才自动审核 (autoaudit)。
    - `code_function`: 代码功能类型，例如 `api`、`web`、`crawler`。

    示例：人才集团自动审核后台 API 的代码仓库名称为 `talentgroup-autoaudit-api`  
    人才集团自动审核网页爬虫的代码仓库名称为 `talentgroup-autoaudit-crawler`

### 分支管理
- 主分支应命名为 **main**。
- 新功能和问题修复应从 **main** 分支拉取新分支开发。
- 新功能分支以 **feat/** 为前缀，例如 `feat/user-management`。
- Bug修复分支以 **fix/** 为前缀，例如 `fix/login-error`。
- 完成功能分支或修复分支的开发后，请通过 **Pull Request** 的方式将其合并到 **main** 分支。


