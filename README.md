# Cap or Fact? / 真的假的?

A bilingual (English / 中文) media literacy game for ages 12 to 17.
一款给 12 到 17 岁玩家的中英双语媒介素养游戏。

**Play:** open `index.html` in any modern browser. No install, no build step, no internet needed except for web fonts.
**怎么玩:** 用任意现代浏览器打开 `index.html` 即可,不需要安装,也不需要构建。

## The idea / 设计思路

Fake it first, then catch it. 先造假,再打假。

1. **Forge (造假)** — Pick one of 5 true, boring stories from the town of Maple Ridge and twist it into a viral post over 8 steps, choosing honest, mild or full versions of 8 common tricks. A town map shows the post spreading, and you get a forger score out of 100.
2. **Feed (信息流)** — Switch sides. Posts drawn at random from a pool of 30 land in your feed. Use a limited number of checks (profile, source, image search, date, other coverage, comments), then share, scroll past, ask for the source, or flag as fake.
3. **Results (结果)** — See how many people believed fakes or got the facts, review every call, and take away the SIFT method.

Seeing the tricks from the inside works like a vaccine ("prebunking"). In a Cambridge study of the game *Bad News*, players rated fake news as 21% less reliable after playing (Roozenbeek & van der Linden, *Palgrave Communications*, 2019). On Twitter, false stories were 70% more likely to be reshared than true ones (Vosoughi, Roy & Aral, *Science*, 2018).

## Features / 功能

- Four difficulty levels (Easy, Normal, Hard, Expert with a 30-second timer) / 四档难度
- Step-by-step first-round guide, switchable from the top-right button / 新手引导
- Scene transitions, per-screen colour themes, right/wrong feedback with sound / 转场、主题色、答题反馈与音效
- Fully bilingual, works on desktop and phone / 中英双语,桌面和手机都能玩

## Code / 代码

Everything is in one file, `index.html`: plain HTML, CSS and JavaScript with no dependencies. Content (stories, posts, tricks, interface text) sits in data objects at the top of the script, so new posts or stories can be added without touching the game logic.
所有代码都在 `index.html` 一个文件里,原生 HTML/CSS/JS,没有依赖。故事、帖子、手法和界面文字都集中在脚本顶部的数据对象里。

All people, accounts, places, studies and events in the game are fictional.
游戏中的所有人物、账号、地点、研究和事件均为虚构。
