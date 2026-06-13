# 粤语入门 · Cantonese Lessons

零基础粤语入门课程，共 10 课，覆盖九声六调、粤拼、日常会话、俚语、歌词解析等内容。

📖 **在线浏览**：<https://leonezhu.github.io/tiny-lesseson-cantonese/>

## 目录

进入 [课程目录](lessons/0000-toc.html) 查看全部 10 课。

| #   | 课题                            |
| --- | ------------------------------- |
| 01  | [九声六调系统](lessons/0001-jiusheng-liudiao.html) |
| 02  | [粤拼入门](lessons/0002-jyutping-intro.html)      |
| 03  | [常用代词与动词](lessons/0003-common-pronouns-verbs.html) |
| 04  | [数字与量词（粤语特色）](lessons/0004-numbers-classifiers.html) |
| 05  | [吃喝（饮茶/点心/街市）](lessons/0005-yum-cha-dining.html) |
| 06  | [交通与方位](lessons/0006-transportation-directions.html) |
| 07  | [俚语与口头禅](lessons/0007-slang-catchphrases.html) |
| 08  | [时间表达（粤式）](lessons/0008-time-expressions.html) |
| 09  | [社交寒暄与敬语](lessons/0009-shejiao-hanxuan.html) |
| 10  | [粤语歌歌词解析](lessons/0010-cantonese-song-lyrics.html) |

## 目录结构

```
.
├── index.html              # 重定向到 lessons/0000-toc.html
├── .nojekyll               # 禁用 GitHub Pages 的 Jekyll 处理
├── lessons/                # 课程正文（HTML）
│   ├── 0000-toc.html       # 课程目录（实际主页）
│   ├── 0001-jiusheng-liudiao.html
│   └── ...
├── reference/              # 参考速查表（HTML）
├── learning-records/       # 学习记录
├── MISSION.md              # 学习目标
├── NOTES.md
└── RESOURCES.md
```

## 本地预览

任意一种方式：

```bash
# 方式一：Python 内置服务器
python3 -m http.server 8000
# 打开 http://localhost:8000

# 方式二：Node 的 serve
npx serve
```

## GitHub Pages 部署

仓库已配置为 GitHub Pages 站点：

1. 进入仓库 **Settings → Pages**
2. **Source**：`Deploy from a branch`
3. **Branch**：`main` / `(root)`
4. 保存后约 1 分钟，访问 <https://leonezhu.github.io/tiny-lesseson-cantonese/>

根目录的 `index.html` 会自动重定向到 `lessons/0000-toc.html`，让课程目录成为首页，同时保留 `lessons/` 下的编号文件结构。

## 技术说明

- 课程内容全部为静态 HTML，无构建步骤
- `.nojekyll` 防止 GitHub Pages 的默认 Jekyll 处理丢弃以下划线开头的文件
- HTML 由 [TeachHub](https://github.com/leonezhu/teachhub) 生成

## License

个人学习笔记，仅供学习交流。
