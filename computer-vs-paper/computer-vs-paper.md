# IELTS 机考界面实战：机考与纸笔模式对照

> 内容核对日期：2026-11-25。考试安排可能按考试地区变化，请以报名页面和考点通知为准。

本页以 2026 年 IELTS 官方公开信息为依据，聚焦机考答题界面。IELTS 官方于 2026 年 3 月公布，从 2026 年年中起将逐步停止纸笔考试，具体时间因市场而异。部分市场会提供 Writing on Paper 选项，听力、阅读仍在电脑上完成。请不要把该选项误认为完整纸笔考试。

## 核心对比

| 项目 | IELTS on Computer | 纸笔模式 / Writing on Paper |
| --- | --- | --- |
| 听力作答 | 直接在屏幕输入答案，结束后有 2 分钟检查时间 | 传统纸笔模式曾有额外 10 分钟将答案誊到答题纸。该时间不适用于机考。Writing on Paper 选项也不改变听力的机考流程 |
| 阅读界面 | 题目与文章在屏幕上呈现，可使用高亮和笔记工具 | 纸面阅读与作答。2026 年中起纸笔模式将按地区逐步退出 |
| 写作 | 通常在屏幕键入，界面提供字数计数 | 部分地区可选择 Writing on Paper，任务仍显示在屏幕上，答案写在答题纸上 |

## 听力录入实战

下面的 30 秒音频区域是**界面演示占位符**，不会播放 IELTS 真题录音。开始演示后，一边播放占位提示音，一边在文本框练习即时录入。计时结束后只出现 2 分钟检查计时器，不提供 10 分钟誊写环节。

真实考试流程和本组件原型不同。本组件用一段 30 秒演示来练习控件操作，不代表 IELTS 听力录音长度、播放控制或题目安排。

## 阅读分屏模拟器

左侧为文章，右侧为题目。拖动中间分隔条调整列宽。选择文章文字后可高亮，右键文章中的选择可添加笔记。

这些是官方机考介绍中列出的界面辅助功能的练习原型。实际考场的软件外观和交互细节可能随考试平台更新。

## 写作字数与格式校验器

工具会实时统计以空格分隔的英文单词数，并提示是否使用 Tab、是否有段落空行、标点符号后是否留空格。

字数下限属于任务要求：Academic Task 1 和 General Training Task 1 至少 150 词，Task 2 至少 250 词。两项任务均需用完整句子作答，不应写成笔记或项目符号清单。机考写作界面有自动字数计数，但仍需自行检查拼写。

Tab 缩进、空行和标点空格检测是本工具的排版习惯提醒。IELTS 官方公开评分标准没有将“禁止 Tab”“段落必须空一行”或“标点后必须有空格”列为独立评分规则，因此这里不会把提醒标成官方禁令或扣分项。段落和标点仍应保持清晰、正确、易读。

## 官方依据

- [IELTS 关于 2026 年考试交付方式更新的公告](https://ielts.org/news-and-insights/updates-to-ielts-test-delivery)
- [IELTS on computer 考试方式与界面工具](https://takeielts.britishcouncil.org/what-is-ielts/how-it-works/test-modes/ielts-on-computer)
- [British Council 听力考试格式与机考检查时间](https://takeielts.britishcouncil.org/what-is-ielts/how-it-works/test-format/listening)
- [IELTS Academic 写作考试格式、字数和完整句子要求](https://ielts.org/take-a-test/test-types/ielts-academic-test/ielts-academic-format-writing)
- [IELTS Writing on Paper 选项说明](https://ielts.org/take-a-test/test-types/ielts-on-computer-writing-on-paper)

## HTML 原型

同目录下的 `computer-vs-paper.html` 可直接在浏览器打开。所有交互均为前端演示，不连接官方考试系统。

