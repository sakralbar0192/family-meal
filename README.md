# Family Meal

Семейное приложение для рецептов. Ближайшая цель — список рецептов, карточка рецепта и CRUD.

## Стек

Стартуем просто и наращиваем по необходимости:

- **Frontend:** React
- **Backend:** Node.js
- **UI:** ориентир — shadcn/ui (кастом под дизайн Focused Editor)
- **БД:** PostgreSQL (`docker-compose.yaml`)

## Продукт (сейчас)

- Список рецептов
- Просмотр рецепта
- Создание / редактирование
- Удаление (с подтверждением)

Дизайн: Figma, направление **B — Focused Editor** (mobile / tablet / desktop).

## Локально

### База

```bash
docker compose up -d
```

Нужен `.env` с `POSTGRES_USER`, `POSTGRES_PASSWORD`, `POSTGRES_DB`.

### Приложение

Скрипты `dev` / `build` появятся после bootstrap React + Node.
