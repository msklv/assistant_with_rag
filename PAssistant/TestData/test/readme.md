# Получившиеся эксперименты но не пригодившиеся для работы  

Оставлены для иллюстрирования ошибочных решений

## 1. Генерация данных из jira в csv

```text
Сгенерируй набор тестовых данных
- Как будто они экспортированы из Jira 
-  Роль - разработчик C# работающий в платформенной команде  
-  30 шт записей
- с полями 

Тема|Ключ проблемы|Идентификатор проблемы|Тип задачи|Статус|Ключ проекта|Название проекта|Приоритет|Исполнитель|Автор|Создатель|Создано|Обновленo|Дата решения|Описание|Затраченное время|Суммарное затраченое время|Пользовательское поле (В статусе)|Пользовательское поле (Время реализации)|Пользовательское поле (Категория статуса)|Пользовательское поле (Последний спринт)|Комментарий|Комментарий
```

### Результат

Хотя поля и совпадают с реальными данными, но использовать табличный формат не получится, нужен json.
