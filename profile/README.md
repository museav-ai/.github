<p align="center">
  <img src="./logo.svg" width="96" alt="MUSE AV">
</p>

<h1 align="center">MUSE AV · 一念成像</h1>

<p align="center">AI 图像与视频生成中台、短剧工作台和 Agent 工具链。</p>

<p align="center">
  <a href="https://www.museav.top">官网</a> ·
  <a href="https://docs.museav.top">文档</a>
</p>

## 项目

| 仓库 | 做什么 |
|---|---|
| [muse-tv](https://github.com/museav-ai/muse-tv) | 本地短剧与短视频工作台：项目、剧集、镜头、角色库、场景库，出镜、配音、合成成片。原名 reel-kit。 |
| [museav-cli](https://github.com/museav-ai/museav-cli) | MUSE AV 命令行：出图、出视频、模板、素材上传与主体管理，给人和 Agent 在终端里用。 |
| [dsh-museav-assets](https://github.com/museav-ai/dsh-museav-assets) | DeepSeek Harness 插件：按工作区浏览 MUSE AV 素材与出图记录。 |

## 分工

- **中台（MUSE AV）**：角色、场景、生成任务与计费，跨项目共享。
- **muse-tv**：剧集、镜头和成片留在你自己的电脑上。
- **museav-cli**：两者之间的命令行入口，也是 Agent 调用中台的方式。
