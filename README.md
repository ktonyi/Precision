### Отчёт о тестировании
### Краткое описание
Проведено тесирование части кода приложения, отвечающего за начисление бонусов новым клиентам.
В ходе тестирования была выявлена ошибка, которая не позволяет получить точное итоговое значение бонуса.
### Описание тестов
Проведен Smoke-тест части кода приложения, отвечающего за начисление бонусов новым клиентам.
Результат: неверное отображение суммы накопленных бонусов.
### Результаты:
1. 50% успешных тестов.
2. [Баг-репорт](https://github.com/ktonyi/Precision/issues/1)

### Общие рекомендации:
Необходимо что бы значение totalBonus округлялось до десятых.


