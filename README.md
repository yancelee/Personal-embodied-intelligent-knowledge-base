# 具身智能个人知识库 · Personal Embodied Intelligence Knowledge Base

> 一个用于系统化管理「具身智能（Embodied Intelligence）」领域论文与阅读笔记的个人知识库。

本仓库用来沉淀我在具身智能方向阅读过的论文与笔记。论文以 **arXiv ID** 为单位归档，阅读笔记以 **Markdown 文档**保存，并按研究方向（VLA / WM / DEX / RL …）分文件夹归类，方便检索与长期积累。

## 内容组织方式

- **论文（Papers）**：以 arXiv ID 命名（如 `2401.12345`），记录论文元信息（标题、作者、链接、发表时间等）。
- **笔记（Notes）**：以 `.md` 文档形式保存，记录阅读心得、方法拆解、关键公式与个人思考。
- **分类（Categories）**：每个研究方向一个顶层文件夹，论文与笔记归入对应文件夹。

## 方向分类（Taxonomy）

| 文件夹 | 方向 | 说明 |
| --- | --- | --- |
| `VLA` | Vision-Language-Action | 视觉-语言-动作模型，如 RT 系列、OpenVLA、π0、GR00T 等 |
| `WM` | World Model | 世界模型，用于预测与规划，如 Dreamer、JEPA、Genie |
| `DEX` | Dexterous Manipulation | 灵巧操作 / 抓取与手内操作 |
| `RL` | Reinforcement Learning | 强化学习（含模仿学习 IL、离线 RL） |
| `NAV` | Navigation | 机器人导航与探索 |
| `SIM` | Simulation | 仿真平台与数据合成，如 Isaac Lab、SAPIEN、ManiSkill |
| `PER` | Perception | 三维感知 / 场景理解与表征 |
| `PLAN` | Planning | 任务规划 / 长程推理 |
| `HRI` | Human-Robot Interaction | 人机交互 |
| `DATA` | Dataset / Benchmark | 数据集与评测基准 |

> 分类会随阅读推进持续扩展，遇到新方向可新增对应文件夹。

## 目录结构示例

```
Personal-embodied-intelligent-knowledge-base/
├── README.md
├── VLA/
│   ├── 2401.12345/          # arXiv ID 命名的论文目录
│   │   └── paper.md         # 论文元信息
│   └── 2401.12345-notes.md  # 对应的阅读笔记
├── WM/
├── DEX/
├── RL/
└── ...
```

## 使用流程

1. **新增论文**：在对应方向文件夹下创建以 arXiv ID 命名的子目录，写入 `paper.md` 记录元信息。
2. **撰写笔记**：在论文目录下或方向文件夹内创建 `xxx-notes.md`。
3. **维护索引**（可选）：在各方向文件夹的 `README.md` 中维护论文 / 笔记清单，便于速览。

## License

个人学习用途，论文版权归原作者所有，笔记内容遵循论文原始许可证。
