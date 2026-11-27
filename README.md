# CHD CMR Academy

Билингвальный учебный прототип CMR при врождённых пороках сердца. Русский по умолчанию. Статический сайт, без сборки, регистрации или серверного хранения введённых данных.

## Запуск
Откройте index.html в браузере. GitHub Pages: Settings → Pages → Build and deployment → Source → GitHub Actions. Workflow `.github/workflows/pages.yml` validates JavaScript, packages the static site and deploys it on every push to main or manually via Actions → Deploy CHD CMR Academy to GitHub Pages → Run workflow. [Workflow runs](https://github.com/ihaydelka/chd-cmr-academy/actions/workflows/pages.yml).

## Статус
ASD, VSD, PDA, PAPVC — учебные модели, не клинически валидированы. Другие модули зарезервированы. Схемы условные. Alternate, LMS/Z-score и сложная гемодинамика требуют разработки. Лекции и мини-книга — будущие разделы.

## Документация
- [Источники](docs/SOURCES.md)
- [План разработки и проверки](docs/ROADMAP.md)

Перед клиническим применением обязательна независимая проверка формул, допущений, плоскостей измерений и отчётов. Не вводите идентифицирующие данные пациентов. Лицензия пока не предоставлена.
