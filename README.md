### Контекст и задача/цель:
Анализ результатов A/B–тестирования новой механики оплаты на сайте для принятия решения о внедрении её для всех пользователей.

### Используемый стек:
   - Язык программирования:&nbsp;
![Python](https://img.shields.io/badge/Python-blue?logo=python&labelColor=grey)&nbsp;
![Static Badge](https://img.shields.io/badge/SQL-blue?logo=postgresql&logoColor=white&labelColor=grey)&nbsp;
   - Библиотеки: pandas, numpy, scipy.stats (для статистического анализа), seaborn, plotly, matplotlib, os(для поиска и парсинга файлов из папки)
   - Инструменты: JupyterHub, Redash, ClikcHouse

### Этапы работы:
1. Загрузка данных из csv-файлов.<br>
2. Объединение данных и создание общего датафрейма для удобства анализа.<br>
3. Анализ метрик:<br>
    - Подсчет ключевых метрик, таких как конверсия и средний чек (ARPU, ARPAU, CR)<br>
    - Визуализация данных, построение графиков для наглядного представления результатов.<br>
4. Проверка статистической значимости различий между контрольной и экспериментальной группами.<br>
5. Формулировка выводов и рекомендаций по запуску новой механики на всех пользователей.<br>
6. Моделирование ситуации: часть данных поступает после формирования выводов. Учет данных, построение визуализаций.<br>
7. Работа с БД и построение сложных SQL запросов.


### Результат:
В итоге, на основе анализа метрик и статистического тестирования, сделал вывод о том, стоит ли запускать новую механику оплаты на всех пользователей с учетом вновь полученных данных
