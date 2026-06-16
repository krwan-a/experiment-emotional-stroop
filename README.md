# 情绪Stroop颜色命名实验

语义启动 + 情绪Stroop结合范式。纯前端网页，无任何依赖，一键部署 GitHub Pages。

**实验链接**：`https://krwan-a.github.io/experiment-emotional-stroop/`

支持 URL 参数指定被试编号：`?pid=P001`

---

## 实验变量

- **自变量**：词汇类型（积极网络/消极网络/积极普通/消极普通）
- **因变量**：反应时(ms)、正确率、错误率

## 单试次时序

```
注视点(+) 500ms → 空屏 200ms → 启动(深灰词汇) 300ms → 目标(彩色词汇) ≤2000ms → 间隔 800ms
```

按键：红色→**F**、蓝色→**J**、绿色→**K**

## 部署

```bash
git clone https://github.com/krwan-a/experiment-emotional-stroop.git
cd experiment-emotional-stroop
```

本地运行：`python3 -m http.server 8080` → http://localhost:8080

---

修改 `index.html` 中的 `CFG.posNet`/`CFG.negNet` 等数组即可替换实验词汇。
