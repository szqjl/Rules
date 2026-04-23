# Rules

供 **Cursor** 使用的**项目规则**集合：总则 + 四原则细则，可通过 **Remote Rule** 从 Git 仓库导入到各业务项目。

## 仓库里有什么

| 文件 | 说明 |
|------|------|
| `constitution.mdc` | 总则（`alwaysApply: true`），细则用 `@` 引用同目录下文档 |
| `doc/核心四原则.mdc` | 四原则展开条文（`alwaysApply: false`，由总则引用） |

## 在 Cursor 里使用

1. **Cursor Settings** → **Rules** → 当前项目 → **New rule** → **Import from GitHub / GitLab**  
2. 填写本仓库地址（任选其一，以你 Cursor 版本支持为准）：

   - Gitee：`https://gitee.com/philsz/Rules`  
   - GitHub（若为主源）：`https://github.com/szqjl/Rules`

3. 导入后规则一般在：`.cursor/rules/imported/Rules/`。若需更新，可删除该目录后重新导入。

## 与业务仓库的关系

业务项目根目录若另有 **`doc/核心四原则.md`**，以**业务仓库文件为准**；与远程细则冲突时请先对齐或请维护者确认。

## 许可证

本仓库使用 **MIT License**（见 `LICENSE`）。
