# 个人简历 · GitHub Pages

与 [Fenny1993 参考站](https://fenny0527.github.io/Fenny1993/) 相同设计的在线简历模板，内容需自行填写。

## 编辑内容

打开 `index.html`，搜索以下占位符并替换为你的真实信息：

| 占位符 | 位置 |
|--------|------|
| `你的姓名` | 标题、Hero 头部、页脚 |
| `你的职位` / `你的标签` | Hero 头部 |
| `X年+ 相关经验` | 经验年限 |
| `✨ 一句话个人亮点...` | 个人标语 |
| `所在城市` / `your.email@example.com` / `github.com/你的用户名` / `13800000000` | 联系方式 |
| `公司名称 A/B` | 工作经历（复制 `.exp-item` 块可添加更多） |
| `XX+` / `X年` / `XX%` | 关键数据卡片 |
| `亮点项目 1/2/3` | 项目实战记录 |
| `技能 1~8` | 技能标签（复制 `<span class="skill-tag">` 可添加更多） |
| `特质 1~8` | 核心竞争力 |
| `认证/课程 1~4` | 持续学习 |

页面顶部和关键区块有 HTML 注释标注，方便定位。

## 本地预览

```bash
python3 -m http.server 8080
```

浏览器打开 http://localhost:8080

## 部署到 GitHub Pages

1. 在 GitHub 创建新仓库（例如 `personal-resume`）
2. 推送代码：

```bash
git remote add origin https://github.com/你的用户名/personal-resume.git
git add .
git commit -m "Add personal resume page"
git push -u origin main
```

3. 进入仓库 **Settings → Pages**
4. **Source** 选择 `Deploy from a branch`
5. **Branch** 选择 `main`，文件夹选 `/ (root)`
6. 保存后访问 `https://你的用户名.github.io/personal-resume/`
