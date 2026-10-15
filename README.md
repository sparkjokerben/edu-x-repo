# edu-x 官方发行仓

edu-x 桌面应用的分发事实源（edu-x 主仓不含任何对外发布物）：

- **Releases**：客户端安装包（dmg/zip/exe）、`latest-mac.yml`/`latest.yml`
  （应用更新用）与 blockmap。下载与更新一律经我们的域名反代
  （`https://edu-x.goof.com.cn/repo/…`），老师机不直连 GitHub。
- **`catalog.json`：官方扩展目录**（中文名、说明、数据范围、可装版本）。
- **`registry/<包名>` 与 `registry/<包名>-<版本>.tgz`**：扩展安装的静态
  npm registry（pnpm 只需这两个文件）。安装端 `https://edu-x.goof.com.cn/repo/registry/`。

内容全部由主仓的发行流水线自动生成与提交；请勿手工编辑。
