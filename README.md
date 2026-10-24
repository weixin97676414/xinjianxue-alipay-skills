# 心鉴学 · 六款付费解读 Skill

六个自包含的 AI Skill 包，覆盖八字、占星本命、占星运势、塔罗、梅花易数、人性深度剖析。每个包内 `SKILL.md` 为入口，`references/` 下是接口、解读与付款说明。

## 技能列表

| Skill | 说明 |
|---|---|
| [`xinjianxue-bazi`](xinjianxue-bazi/SKILL.md) | 八字命理：四柱、五行强弱、起运、十步大运与流年 |
| [`xinjianxue-western-astrology`](xinjianxue-western-astrology/SKILL.md) | 占星本命盘：日月升、十大行星落座、主要相位与本命结构 |
| [`xinjianxue-astro-transit`](xinjianxue-astro-transit/SKILL.md) | 占星运势：本命盘叠加当下行运，看议题、压力点与机会窗口 |
| [`xinjianxue-tarot`](xinjianxue-tarot/SKILL.md) | 塔罗：50 种牌阵，按用户报号依次出牌并解读 |
| [`xinjianxue-meihua`](xinjianxue-meihua/SKILL.md) | 梅花易数：用户报两个数起卦，得本卦、互卦、变卦、体用与卦辞 |
| [`xinjianxue-relation-advisor`](xinjianxue-relation-advisor/SKILL.md) | 人性深度剖析：生成特征编码画像，判度＋双链条解析关系与处境 |

## 目录结构

```
<skill>/
├── SKILL.md
└── references/
    ├── api.md       # 接口与请求示例
    ├── payment.md   # 付款与鉴权
    └── reading.md   # 解读口径
```

`xinjianxue-tarot` 另含 `references/spreads.md`（50 种牌阵定义）。

## 使用

把整个 `<skill>/` 目录放进 AI 的 skills 目录，或按 `SKILL.md` 的 frontmatter 注册后即可调用。

## 授权

仓库内容版权归作者所有，仅供授权渠道分发使用。
