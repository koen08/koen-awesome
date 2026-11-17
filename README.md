# koen-awesome

Подборка полезных утилит и расширений для работы с GitHub. Список живой — обновляется по мере находок.

## Содержание

- [GitHub CLI](#github-cli)
- [Расширения GitHub CLI](#расширения-github-cli)
- [GitHub Actions и CI](#github-actions-и-ci)
- [Разное](#разное)
- [Как установить расширение](#как-установить-расширение)

## GitHub CLI

- **[GitHub CLI](https://github.com/cli/cli)** — официальный клиент `gh`: pull request'ы, issues, workflow и релизы прямо из терминала.

## Расширения GitHub CLI

- **[gh-dash](https://github.com/dlvhdr/gh-dash)** — настраиваемый TUI-дашборд с PR и issues, не выходя из терминала.
- **[gh-poi](https://github.com/seachicken/gh-poi)** — безопасно находит и удаляет локальные ветки, уже влитые в основную.
- **[gh-branch](https://github.com/mislav/gh-branch)** — нечёткий поиск и быстрое переключение между ветками, удаление веток.
- **[gh-f](https://github.com/gennaro-tedesco/gh-f)** — компактный fzf-навигатор по репозиториям, PR и issues.
- **[gh-s](https://github.com/gennaro-tedesco/gh-s)** — интерактивный поиск репозиториев на GitHub.
- **[gh-q](https://github.com/kawarimidoll/gh-q)** — клонирование репозиториев через fzf и [ghq](https://github.com/x-motemen/ghq).
- **[gh-pr-review](https://github.com/agynio/gh-pr-review)** — inline-комментарии ревью: просмотр, ответы и resolve тредов из терминала.
- **[gh-notify](https://github.com/meiji163/gh-notify)** — уведомления GitHub в терминале.
- **[gh-sub-issue](https://github.com/yahsan2/gh-sub-issue)** — управление подзадачами (sub-issues) из CLI.
- **[gh-workflow-stats](https://github.com/fchimpan/gh-workflow-stats)** — статистика успешности и длительности workflow и job'ов.
- **[gh-clone-org](https://github.com/matt-bartel/gh-clone-org)** — клонирование всех репозиториев организации с фильтрами по топикам.
- **[gh-act](https://github.com/nektos/gh-act)** — запуск GitHub Actions локально через `act` из `gh`.
- **[gh-secure](https://github.com/GitHubSecurityLab/gh-secure)** — включает security-функции репозитория по best practices GitHub Security Lab.
- **[gh-skyline](https://github.com/github/gh-skyline)** — генерирует 3D-модель истории вкладов GitHub.
- **[gh-graph](https://github.com/kawarimidoll/gh-graph)** — график вкладов прямо в терминале.

## GitHub Actions и CI

- **[act](https://github.com/nektos/act)** — локальный запуск GitHub Actions в Docker без пуша в репозиторий.
- **[actionlint](https://github.com/rhysd/actionlint)** — статический линтер workflow-файлов GitHub Actions.
- **[reviewdog](https://github.com/reviewdog/reviewdog)** — автоматические комментарии ревью в PR от любого линтера.
- **[git-cliff](https://github.com/orhun/git-cliff)** — генератор changelog из истории коммитов по Conventional Commits.

## Разное

- **[ghorg](https://github.com/gabrie30/ghorg)** — массовое клонирование и бэкап репозиториев организаций (GitHub, GitLab, Bitbucket).
- **[refined-github](https://github.com/refined-github/refined-github)** — расширение браузера, которое упрощает интерфейс GitHub и добавляет полезные функции.
- **[github1s](https://github.com/conwnet/github1s)** — открывает любой репозиторий в VS Code прямо в браузере (добавьте `1s` после `github` в URL).
- **[awesome-gh-cli-extensions](https://github.com/kodepandai/awesome-gh-cli-extensions)** — большой каталог расширений для GitHub CLI.

## Как установить расширение

```bash
gh extension install <owner>/<repo>
```

Например:

```bash
gh extension install dlvhdr/gh-dash
```

Обновить все установленные расширения:

```bash
gh extension upgrade --all
```
