# 品牌图片更新指南

本指南帮助你快速生成包含"呼吸节奏 RQrunning"品牌的社交媒体图片。

## 📸 需要更新的图片

1. **og-image.png** - Open Graph 社交分享图片 (1200x630)
2. **apple-touch-icon.png** - iOS 主屏幕图标 (180x180)
3. **favicon.svg** - 网站图标 (可选更新)

---

## 🎨 方案 A：使用提供的 HTML 模板（推荐）

### 步骤 1：生成 OG 图片

1. 打开 `og-image-template.html`
2. 点击"隐藏说明"按钮
3. 使用截图工具截取整个黑色卡片（1200x630）
4. 保存为 `og-image.png`，替换项目根目录中的旧文件

**截图技巧：**
- Windows：`Win + Shift + S` 或使用 Snipping Tool
- Mac：`Cmd + Shift + 4`，然后按空格选择窗口
- 推荐使用 [Shottr](https://shottr.cc/)（Mac）或 [ShareX](https://getsharex.com/)（Windows）精确截图

### 步骤 2：生成 Apple Touch Icon

1. 打开 `apple-touch-icon-template.html`
2. 点击"隐藏说明"按钮
3. 截取 180x180 的正方形图标
4. 保存为 `apple-touch-icon.png`，替换项目根目录中的旧文件

---

## 🖼️ 方案 B：使用在线设计工具

### Canva（免费）

1. 访问 [Canva](https://www.canva.com/)
2. 选择"自定义尺寸"：
   - OG 图片：1200 x 630 px
   - Apple Touch Icon：180 x 180 px

3. 设计要点：
   - **背景**：深灰黑色渐变 (#1a1a1a → #0f0f0f)
   - **主色**：荧光绿 #00ff88
   - **辅助色**：青色 #00d9ff
   - **字体**：Inter 或 思源黑体

4. 元素布局（OG 图片）：
   ```
   ┌────────────────────────────┐
   │ ● 呼吸节奏                 │
   │   BREATHING RHYTHM         │
   │                            │
   │ 🏃 跑步训练强度仪表盘      │
   │                            │
   │ 心率区间·呼吸商 RQ·配速预测│
   │                            │
   │ [科学训练] [实时联动]      │
   └────────────────────────────┘
   ```

### Figma（免费）

1. 访问 [Figma](https://www.figma.com/)
2. 创建 1200x630 和 180x180 画布
3. 使用渐变、文字、图形工具设计
4. 导出为 PNG（2x 质量）

---

## 🎯 设计规范

### 颜色
- **主色（荧光绿）**：`#00ff88` - 用于品牌名、关键文字
- **辅助色（青色）**：`#00d9ff` - 用于副标题、装饰
- **警告色（橙色）**：`#ff6b35` - 用于强调
- **背景（深灰）**：`#1a1a1a` - 主背景
- **背景（更深）**：`#0f0f0f` - 渐变底色

### 字体
- **中文**：思源黑体 / Microsoft YaHei
- **英文**：Inter / Roboto
- **标题大小**：56-64px（OG）/ 24px（Icon）
- **副标题大小**：28-32px（OG）/ 10px（Icon）

### 品牌元素
- **Logo 圆点**：荧光绿圆形，带发光效果
- **运动感**：使用跑步 emoji 🏃
- **科技感**：可加心率波形、渐变光晕

---

## ✅ 验证清单

更新完成后，检查：

- [ ] OG 图片尺寸正确（1200x630）
- [ ] Apple Touch Icon 尺寸正确（180x180）
- [ ] 品牌名"呼吸节奏"清晰可读
- [ ] 英文名"RQrunning"或"Breathing Rhythm"可见
- [ ] 颜色符合品牌规范（荧光绿主色）
- [ ] 文件大小合理（OG < 200KB, Icon < 50KB）
- [ ] 在社交媒体预览工具测试：
  - [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
  - [Twitter Card Validator](https://cards-dev.twitter.com/validator)
  - [LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/)

---

## 📝 更新后操作

1. **替换文件**：
   ```bash
   # 备份旧文件（可选）
   mv og-image.png og-image-old.png
   mv apple-touch-icon.png apple-touch-icon-old.png
   
   # 放入新文件（从截图或下载的位置）
   cp ~/Downloads/og-image.png .
   cp ~/Downloads/apple-touch-icon.png .
   ```

2. **提交到 Git**：
   ```bash
   git add og-image.png apple-touch-icon.png
   git commit -m "chore: 更新品牌图片，反映「呼吸节奏 RQrunning」新品牌"
   git push origin main
   ```

3. **清除缓存**：
   - 使用 Facebook Debugger 刷新缓存
   - 等待 24-48 小时让社交平台更新

---

## 🎨 设计灵感

参考这些运动科技品牌的视觉风格：
- **Nike Run Club** - 简洁、高对比度
- **Strava** - 橙色主题、数据可视化
- **Garmin Connect** - 深色背景、荧光色点缀
- **Whoop** - 极简黑底、绿色强调

---

## 💡 提示

- 保持简洁，信息层次清晰
- 荧光绿要"发光"（使用阴影/模糊效果）
- 移动端预览时文字仍需清晰
- 可加入心率波形、运动轨迹等元素增强运动感

---

## 🤝 需要帮助？

如果遇到问题：
1. 检查浏览器控制台是否有错误
2. 确保截图工具支持精确尺寸
3. 可以使用在线压缩工具优化文件大小：[TinyPNG](https://tinypng.com/)

祝设计愉快！🎨
