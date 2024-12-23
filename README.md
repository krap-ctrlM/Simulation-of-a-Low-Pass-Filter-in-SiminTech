# Simulation of a Low-Pass Filter in SiminTech

### Описание
Проект посвящен моделированию низкочастотного фильтра в системе SiminTech. Цель работы — изучить поведение фильтра в условиях различных видов шума и проверить выполнение заданных ограничений на амплитуду и фазовый сдвиг сигнала.

### Задачи
1. Построение модели низкочастотного фильтра.
2. Исследование поведения фильтра при:
   - Равномерном шуме.
   - Нормальном шуме.
3. Вывод информативных графиков сигнала.

---

### Технические условия
1. Частота квантования: \((2\pi / 10N)\).
2. Затухание на частоте квантования: не менее 3 дБ.
3. Амплитуда полезного сигнала: не менее \(2.5 \times N\).
4. Сдвиг фазы на частоте полезного сигнала: не более \(\pi / 18\).

---

### Этапы моделирования
1. **Настройка параметров графиков:**
   - `Start_time = 0`.
   - `End_time`: рассчитывается в зависимости от периода.
   - Установка минимального и максимального шага для повышения информативности.
2. **Построение временных периодов:**
   - Первый период: параметры базового сигнала.
   - Второй период: исследование шума.
   - Третий период: финальная настройка параметров.
3. **Анализ:**
   - Построение графиков выходного сигнала.
   - Проверка ограничений на амплитуду и фазу.

---

### Вывод
В ходе моделирования:
- Расчеты фильтра показали затухание на частоте квантования не менее 3 дБ.
- Амплитуда полезного сигнала на выходе составила не менее \(2.5 \times N\).
- Фазовый сдвиг на частоте полезного сигнала удовлетворяет заданному ограничению \(\pi / 18\).

---


