# 性欲望测试 · 16/64题（GitHub Pages 版）

一个纯前端、隐私友好的性欲望自测页面，支持 **16 / 64 题** 切换、移动/桌面自适应、雷达图与子维度表格、结果 PNG 导出。

- 技术栈：原生 HTML + Tailwind CSS (CDN) + Chart.js (CDN)
- 部署：开箱即用，直接推送到 GitHub，开启 GitHub Pages 即可上线
- 隐私：所有计算在**浏览器本地**完成，不上传数据；含 18+ 年龄闸

## 线上预览（启用 GitHub Pages 后）
`https://<你的GitHub用户名>.github.io/sex-desire-test/`

---

## 本地预览
直接双击 `index.html` 即可。

## 部署到 GitHub Pages（分支：`main`）
1. 新建仓库 **sex-desire-test**（保持与文件夹同名更省心）。
2. 在本地或 Codespaces：
   ```bash
   git init
   git branch -M main
   git remote add origin https://github.com/<你的GitHub用户名>/sex-desire-test.git
   git add .
   git commit -m "init: sex desire test 16/64"
   git push -u origin main
   ```
3. 打开仓库的 **Settings → Pages**：
   - Source 选择 **Deploy from a branch**
   - Branch 选择 **main**, `/ (root)`
   - 点击 **Save**，等待几分钟生效。
4. 访问 Pages 提供的 URL（如：`https://<你的GitHub用户名>.github.io/sex-desire-test/`）

## 自定义域名（可选）
- 在 `Settings → Pages` 里设置你的域名（例如 `test.aimiidea.space`）。
- 在你的域名 DNS 添加 `CNAME` 指向 `<你的GitHub用户名>.github.io`。
- 可在仓库根目录添加 `CNAME` 文件（只写一行你的域名），示例：
  ```
  aimiidea.space
  ```

## 许可协议
本项目采用 MIT License，详见 `LICENSE`。

---

## 功能说明
- 16题 / 64题 可切换
- 4 大维度：DF（欲望频率）、IF（主动与幻想）、PC（心理情境）、PL（身体与生活方式）
- 8 个子维度（仅 64 题展示详细分数与建议）：
  - DF-I 欲望强度、DF-T 诱发情境
  - IF-N 主动性、IF-E 新鲜感探索
  - PC-S 压力/情绪、PC-R 关系安全感
  - PL-S 睡眠与精力、PL-M 物质与疾病
- 反向计分处理、进度条、结果雷达图、PNG 导出

> 免责声明：本测试仅供成人进行自我了解，结果为一般性参考信息，不构成医学或心理诊断。如对自身身心健康有疑问，请咨询专业医生或心理咨询师。
