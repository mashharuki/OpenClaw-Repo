# OpenClaw-Repo

OpenClawに関する使い方を学習・検証するためのリポジトリ

## ワークスペース設定

```bash
~/.openclaw/
├── openclaw.json      # メイン設定ファイル
├── workspace/         # エージェントのホーム
│   ├── AGENTS.md      # 行動指針
│   ├── SOUL.md        # ペルソナ・口調設定
│   ├── USER.md        # ユーザー情報
│   ├── MEMORY.md      # 長期記憶
│   ├── TOOLS.md       # ツール設定メモ
│   └── memory/        # 日次ログ
├── skills/            # カスタムスキル
└── browser/           # ブラウザデータ
```

## SKillの追加の仕方

```bash
npx clawhub@latest install sonoscli
```

## 参考文献
- [OpenClaw チートシート｜これだけ覚えればOKなコマンド・設定・ワークフロー集](https://qiita.com/akira_papa_AI/items/f3d52c314329127b3bba)
- [OpenClawの"魂"が盗まれる？ — AIエージェント時代のセキュリティ対策
](https://zenn.dev/komlock_lab/articles/056409c7dcbe4d)
- [OpenClaw 設定ガイド──マルチエージェント・Web検索・メモリ検索](https://note.com/major_elk2890/n/n473367d34bf9)
- [Agent Skill マーケットプレイス](https://skillsmp.com/ja)
- [GitHub heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills/blob/main/README.ja.md)
- [【効率爆UP】Agent Skillsの探し方！おすすめ公開サイト3選と導入手順](https://note.com/masa_wunder/n/n227040a2e1c6)
- [ClawHub](https://clawhub.ai/)
