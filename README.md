# 一起学雅（ielts-learning）

## 这是啥

备考雅思期间，我被下面这两件事小小的困扰了一下，于是自己攒了这个：

- **背词的**：想上传自己整理的生词和词组到背词软件，结果只让输单词，短语词组都不支持。于是某天刷小红书的时候受到了小红书博主 @BATACO云天 的同义替换程序帖子的启发，在这个同替小程序的基础上，自己也vibe-coding增设了可上传自己词书/短语/同替词和记忆复习功能。
- **听写的**：听写王陆语料库时，我发现单词间隔时间很短，尤其是听写复杂单词或短语时，单词还没写完就跳到下一个了，明明有些单词我并不是不会拼写。所以干脆自己写了一个听写的小程序，间隔随便调。

没有后端，没有 App，打开就能用，支持手机端和电脑端。

如果觉得能用就 star 一下呀，祝大家屠雅顺利。

> 学习进度与上传内容仅保存在本机浏览器，不会上传服务器。

## 页面说明

| 文件 | 功能 |
|------|------|
| `一起学雅.html` | 整合了单词听写 / 同义替换，并另外增设了 词汇闯关 模块|
| `单词听写.html` | 上传 TXT 词表，朗读听写；输入答案自动判分，答对自动进入下一词 |
| `538雅思同义替换学习复习小程序.html` | 雅思 538 考点词刷词 + 记忆复习（错词本） |

### 一起学雅

<img width="1897" height="908" alt="image" src="https://github.com/user-attachments/assets/62e9feb0-14dc-4d57-a28a-be4e1b88bbc1" />
<img width="1084" height="2165" alt="9a93d718d199416cf6767d5e3e6171f" src="https://github.com/user-attachments/assets/de330e0b-551c-4a14-a7e2-c8baae560d42" />

### 单词听写

- 上传每行一词的 `.txt`，或使用内置示例
- 朗读后在输入框作答，回车判分
- 答对：约 0.8 秒后自动跳到下一词
- 答错 / 看答案：显示正确答案，手动点「下一个」继续
- 全部完成后可一键**复盘错词**
- 未作答：按设定间隔自动滚词（可当作跟读模式）

<img width="1896" height="915" alt="image" src="https://github.com/user-attachments/assets/d9619d88-6ede-4e45-9568-ea4a742e1c6e" />
<img width="1084" height="2165" alt="84d16ab411dc8ea0dca8413490beaef" src="https://github.com/user-attachments/assets/b96cbdba-797b-480a-91a0-a760102b083f" />

### 同义替换

- 内置 538 同义替换，先回忆再翻卡
- 错词自动进入复习模式，支持记忆进度本地保存
- 也可上传自定义「单词 + 释义 / 同义替换」，短语词组也能录

<img width="1900" height="917" alt="image" src="https://github.com/user-attachments/assets/75569ed3-0186-4c1d-8475-9b536ee77dba" />
<img width="1084" height="2164" alt="7e6ca2f60fc651fd5ef5abdeba177d8" src="https://github.com/user-attachments/assets/f9fc3036-c2cf-4d1d-b178-e0d057458ad4" />


### 词汇闯关

- 60 秒限时答题，连击加分
- 题目来自自定义词表，词表充足时支持听音选词

<img width="1898" height="918" alt="image" src="https://github.com/user-attachments/assets/fe4ec927-2229-4aa6-8dd0-dc54c22d10e3" />
<img width="1084" height="2151" alt="a96dacf108515cd64a1e44f7c28c46c" src="https://github.com/user-attachments/assets/8ae4e78d-9684-4c7c-8975-24cfca3ea4f0" />

## 本地使用

直接双击对应 `.html` 文件，或用任意静态服务器托管本目录。

## 出处致谢

- **同义替换 / 538 模块**源自小红书博主 [BATACO云天](https://www.xiaohongshu.com/explore/696bbe49000000001a0301c9) 的原始作品，并新增记忆复习功能。
- **单词听写、词汇闯关**等其余功能为本项目原创或在其基础上扩展。

## License

仅供个人学习使用。二次分发请保留原作者出处说明。
