# 🎓 ITMO Portfolio

Сайт-портфолио лабораторных работ на MkDocs Material. Отчёты, навигация по семестрам и исходники сайта собраны в одном репозитории.

| Каталог | Назначение |
| --- | --- |
| `src/` | MkDocs: конфигурация и Markdown-страницы |
| `docs/` | Сохранённая сборка сайта и описание источника |
| `.sourcecraft/` | Конфигурация публикации на исходной платформе |

## Локальный просмотр

```sh
python -m pip install mkdocs mkdocs-material
cd src
python -m mkdocs serve
```

Откройте `http://127.0.0.1:8000`. Сборка: `python -m mkdocs build -d ../docs` из `src/`.

Публичная копия [artemmasterov8/portfolio](https://sourcecraft.dev/artemmasterov8/portfolio). [Исходное описание](docs/source-readme.md). Развёртывание GitHub Pages для этого нового репозитория не настраивалось; исходный сайт остаётся самостоятельным проектом.
