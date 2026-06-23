# humaniser - убери AI-измы

Скилл для Claude Code: финальная антиклише-зачистка текста. Находит нейросетевые паттерны (ложная глубина, фальшивая близость, пустые связки, канцелярит, рубленые фразы, длинные тире, шаблонные призывы) и переписывает их в живую человеческую речь, ничего не выдумывая.

## Установка

Нужен установленный [Claude Code](https://docs.claude.com/claude-code) и `git`. Выполни блок под свою систему.

**macOS / Linux** (Терминал):
```bash
mkdir -p ~/.claude/skills
git clone https://github.com/theivansergeev/humaniser ~/.claude/skills/humaniser
```

**Windows** (PowerShell):
```powershell
New-Item -ItemType Directory -Force "$HOME\.claude\skills" | Out-Null
git clone https://github.com/theivansergeev/humaniser "$HOME\.claude\skills\humaniser"
```

Нет `git`? Поставь: macOS - `xcode-select --install`; Windows - [git-scm.com/download/win](https://git-scm.com/download/win) (или `winget install Git.Git`)

Перезапусти Claude Code - скилл подхватится сам.

## Как пользоваться

Скажи Claude любую из фраз:
- «Прогони этот текст через humaniser»
- «Убери нейросетевые клише / AI-паттерны»
- «Сделай текст более человечным»
- «Причеши стиль»

Опционально: если у тебя есть файл с профилем своего голоса, скилл подстроит правки под него. Без него работает по общим антиклише-правилам.

## Автор

Иван Сергеев - вайбмаркетинг и вайбкодинг для тех, кто начинает с нуля. https://theivansergeev.ru
