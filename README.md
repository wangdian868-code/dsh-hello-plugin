# DSH Hello Plugin

这是一个用于测试 DeepSeek Harness Desktop 插件安装功能的示例项目。

## 插件介绍

- 插件名称：dsh-hello-plugin
- 当前版本：0.1.0
- 开发语言：JavaScript
- 插件类型：DSH Bundle Plugin
- 功能：验证 GitHub 插件安装和加载流程

## 安装方法

首先确保已经安装 DeepSeek Harness Desktop，并完成首次启动。

通过桌面端系统托盘菜单打开 Open DSH Terminal，然后完全退出桌面端。

在刚才打开的终端中执行：

```powershell
dsh plugin --profile desktop add github:wangdian868-code/dsh-hello-plugin
```

安装完成后，重新启动 DeepSeek Harness Desktop。

## 验证方法

查看 Harness 的运行日志。

插件成功加载后，预期输出：

```text
[dsh-hello-plugin] Plugin loaded successfully from GitHub!
```

注意：这是一个测试插件，不会在聊天界面增加按钮，也不会自动创建 AI Skill。

## 更新插件

```powershell
dsh plugin --profile desktop update
```

更新后重新启动桌面端。

## 卸载插件

```powershell
dsh plugin --profile desktop remove dsh-hello-plugin
```

## GitHub

https://github.com/wangdian868-code/dsh-hello-plugin
