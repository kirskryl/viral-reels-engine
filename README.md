# Viral Reels Engine

Скилл для Codex / Cursor / Claude: вирусные сценарии Reels / Shorts / TikTok (разбор 945 реальных роликов).

Ниша — **обязательный параметр**: скилл спрашивает нишу и аудиторию, не фиксируется на отношениях/психологии/здоровье.

Парный скилл для текста в Telegram: [viral-posts-engine](https://github.com/kirskryl/viral-posts-engine).

## Триггеры

`/viral-reels`, `/viral-reels-engine`.

Только по явной команде (`disable-model-invocation: true`).

## Установка

### Codex

```bash
git clone https://github.com/kirskryl/viral-reels-engine.git ~/.codex/skills/viral-reels-engine
```

В `~/.codex/config.toml`:

```toml
[features]
skills = true
```

### Cursor / Claude

```bash
git clone https://github.com/kirskryl/viral-reels-engine.git ~/.cursor/skills/viral-reels-engine
ln -sfn ~/.cursor/skills/viral-reels-engine ~/.claude/skills/viral-reels-engine
```

## Обновление

```bash
git -C ~/.codex/skills/viral-reels-engine pull
# или
git -C ~/.cursor/skills/viral-reels-engine pull
```

## Лицензия

MIT — см. [LICENSE](LICENSE).
