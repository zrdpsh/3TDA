## Игровой процесс

- GameState — Текущее состояние игры - ожидание ввода, проверка совпадений, применение бонусов, завершение игры.

- GridState - инкапсулирует текущее состояние игрового поля.

- Command — Модель отдельного хода игрока (позволяет реализовать отмену/повтор).

## Совпадения и бонусы
- Match — Совпадение: представление найденной группы ячеек одного типа.

- Combo — Комбо, объединение нескольких совпадений, начисление дополнительных бонусов за серию.

## Игровая модель
- Cell — Ячейка игрового поля: тип содержимого, возможно положение.

- Grid — Игровое поле: массив ячеек, управление размещением, перестановками и очисткой совпадений.

- Score — обёртка над числом очков - инкапсулирует добавление, обнуление и получение значения.

- PlayerInput — Выбор пар ячеек игроком для перестановки.
