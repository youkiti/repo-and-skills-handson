# ハンズオンカフェ: リポジトリ運用と Skills

SRWS-PSG ハンズオンカフェ (2026-06-24) 用のデモリポジトリです。

## このリポジトリの使い方

1. このリポジトリを **fork** または **clone** してください
2. ハンズオン中に `.gitignore` の編集、Issue 作成、Branch + PR の流れを体験します
3. `.claude/skills/` にある Skill を呼び出し、`SKILL.md` を書き換える演習を行います

## 構成

```
.
├── README.md              ← このファイル
├── .gitignore             ← Part 1 で編集する (ビフォー状態)
├── .claude/
│   └── skills/
│       ├── check-handson-env/
│       │   └── SKILL.md   ← 環境チェック用 Skill (/check-handson-env)
│       └── humanizer-academic/
│           └── SKILL.md   ← Part 2 で description を書き換える演習用 Skill
└── draft.md               ← Skill の動作確認用サンプル文書
```

## 事前準備

以下がすべて済んでいることを確認してください:

- [ ] Antigravity が起動する (Claude Code / Codex 拡張でも可)
- [ ] GitHub に push できる (PAT またはブラウザ認証)
- [ ] ブラウザ版 Claude にログインできる
- [ ] Zenodo Sandbox ([sandbox.zenodo.org](https://sandbox.zenodo.org/)) にログインできる

> 環境チェックは Antigravity で `/check-handson-env` と入力すると自動で確認できます。
