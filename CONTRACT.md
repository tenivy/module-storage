# CONTRACT.md
Модуль: module-storage
Проект: TaskManager
Версия: 1.0

---

## 1. Описание функций

- create_task — создание новой задачи
- get_all_tasks — получение списка задач
- complete_task — завершение задачи

---

## 2. Параметры

create_task:
- title (строка)
- description (строка)

get_all_tasks:
- параметры отсутствуют

complete_task:
- task_id (число)

---

## 3. Формат возвращаемых данных

create_task:
- возвращает задачу

get_all_tasks:
- возвращает список задач

complete_task:
- возвращает true или false

---

## 4. Примеры использования

create_task("Купить книгу", "Купить учебник")

get_all_tasks()

complete_task(3)