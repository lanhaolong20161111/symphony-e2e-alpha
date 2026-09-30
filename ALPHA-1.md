---
id: ALPHA-1
title: "E2E e2e-alpha ticket 1"
state: in-progress
priority: 1
---
**只做这一件事，不要探索仓库、不要跑测试套件、不要读别的文件**（省 token ✓）。

在 `README.md` 最后追加**一行**：

```
alpha-e2e-1
```

## Validation

    findstr /C:"alpha-e2e-1" README.md

## 完成时的动作

1. 自己提交（信息写清改了什么）✓
2. 自己 push：`git push -u origin symphony/ALPHA-1` ✓
3. 自己开 PR：`gh pr create`（base 主分支）✓
4. 用 `ticket_comment` 报告：提交哈希与主题 ✓、push 退出码 ✓、PR 链接 ✓、**凭据前 4 字符** ✓（ghs_ = App 令牌 ✓）、**PR 是你开的还是宿主开的** ✓
5. 票改成 `state: in-review` ✓