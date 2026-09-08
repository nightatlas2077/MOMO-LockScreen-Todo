# MOMO 锁屏清单

把 iPhone 锁屏变成一张待办清单。基于 Apple 快捷指令实现，无需单独开发 App，即可在锁屏界面查看待办，并随时快速添加新事项。

## 快捷指令

| 名称 | 说明 | 链接 |
| --- | --- | --- |
| 主指令 | 锁屏待办清单主流程 | [安装](https://www.icloud.com/shortcuts/bf6fe5c1031541c79472a9ec61fed295) |
| 添加待办到锁屏指令 | 快速把新待办添加到锁屏清单 | [安装](https://www.icloud.com/shortcuts/0c518d0d25d24990a88e17f681b47f03) |
| 配置教程 | 首次安装与配置教程 | [安装](https://www.icloud.com/shortcuts/e7ecf6fc86794c2ca9c00e1dabd4ebf7) |

## 使用步骤

1. 先在 iPhone 上安装「配置教程」并按其指引完成设置。
2. 安装「主指令」与「添加待办到锁屏指令」。
3. 在锁屏添加对应小组件，即可在锁屏直接查看待办。
4. 日常通过「添加待办到锁屏指令」随时补充事项。

> 具体安装与配置细节以「配置教程」快捷指令内的步骤为准。

## 目录结构

```
.
├── shortcuts.md              # 三个快捷指令的 iCloud 链接
├── README.md
└── resource/
    └── reminde_design.html   # 锁屏待办界面原型（MOMOLOCKTODO V1）

```

## 技术说明

- 运行环境：Apple 快捷指令 + iOS 锁屏小组件
- 界面原型：`resource/reminde_design.html` 为纯 HTML/CSS 实现的锁屏待办界面效果稿，用于预览产品形态
- 待办支持分组（收集箱 / 项目清单 / 等待清单）、旗标、子任务、紧急标记与截止日期（参照原型设计）

## License

MIT License，详见 [LICENSE](LICENSE)。