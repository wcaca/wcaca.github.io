# wcaca.github.io

**主入口**: https://wcaca.github.io/

## 部署清单

| 路径 | 项目 | 大小 | 访问 |
|------|------|------|------|
| `/` | **landscape-engine** · 内在风景 3D 渲染器 | 44KB | https://wcaca.github.io/ |
| `/atm/` | **动中觉察** · 费登奎斯 12 节课主站 | 13MB | https://wcaca.github.io/atm/ |

## 部署记录

### v25cj (2026-06-18) — ATM 主站
- 源: https://github.com/wcaca/atm-redirector/tree/main/site
- 13MB 完整主站 (assets + 12 节课 audio + videos)
- 路径资源改相对路径
- GitHub Pages 自动部署

### v25ci (2026-06-18) — landscape-engine
- 源: https://github.com/wcaca/landscape-engine
- 913 行 Three.js 内在风景渲染器
- 永久公网访问

## 部署策略

按用户偏好：
- 沙箱跑 1 周 → 升级到 163.7.3.92 + cloudflared
- 新项目先 MiniMax 沙箱试，再决定要不要推 GitHub Pages
- 主入口 (root) 给最有代表性的项目（landscape-engine）
- 子路径放其它成熟 web 项目
