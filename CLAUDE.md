@AGENTS.md

# Claude Code adapter

Общие правила импортированы выше.

- Проектный skill — `.claude/skills/workshop-copilot/SKILL.md`, вызов `/workshop-copilot`. Копия в `.agents/skills` — для Codex, это тот же workflow, а не второй.
- Режим Auto пользователь выбирает в переключателе у поля ввода; проектный файл его не включает.
- `.claude/settings.json`: запрет чтения секретов, подтверждение перед `git push`, запрет `git push --force` и `git reset --hard`.
- Если у тебя есть глобальные skills или правила для handoff и планов, в этом проекте веди состояние в файлах Starter: `docs/HANDOFF.md`, `PLANS.md`, `docs/PRODUCT.md`.
