# ВебІнвентаріум

Ціль проекту: Створення інструмента для ефективного обліку товарів на складі або в магазині. Вебзастосунок дозволить користувачам вести детальний облік товарів, слідкувати за їхнім рухом, контролювати залишки, робити замовлення та забезпечувати легкий доступ до інформації про товари.

## Автори
- Кіт Евеліна
- Слонівська Соломія

## Основні функціональні вимоги
### Авторизація та аутентифікація користувачів
- Забезпечення можливості реєстрації нових користувачів.
- Вхід до системи з використанням імені користувача та пароля.
- Можливість вибору ролі (адміністратор або оператор складу).

### Інтерфейс користувача
- Вікно реєстрації/авторизації.
- Головне вікно адміністратора - вікно управління користувачами.
- Вікно додавання/редагування товару адміністратора з можливістю фільтрації.
- Головне вікно оператора складу - можливість перегляду та оновлення інформації про кількість товарів після поставок або продажу з можливістю фільтрації.
- Можливість переходу між вікнами та використання "випадаючого" меню.

### Управління товарами
- Додавання, редагування та видалення товарів.
- Можливість додавати фотографії товарів.
- Можливість створення QR-коду для кожного товару.
- Категоризація товарів для зручного пошуку.

### Відстеження руху товарів
- Внесення інформації про прихід і відвантаження товарів.
- Фіксація дати та кількості товарів.

### Планування замовлень
- Відображення рівня запасів товарів.
- Рекомендації щодо потреби у нових замовленнях.

### Документація і підтримка
- Створення інструкції користувача та технічної документації.
- Надання технічної підтримки користувачам.

## Основні нефункціональні вимоги
- Мова інтерфейсу: українська.
- Вимоги до ПЗ:Комп'ютер або мобільний пристрій з доступом до Інтернету. Веб-браузер (наприклад, Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).
- База даних: Використання SQL бази даних для зберігання даних.
- Вимоги по безпеці: Авторизація користувачів перед доступом до функціоналу, можливість встановлення паролів для користувачів та різні рівні доступу (адміністратор, оператор), запобігання втрати даних через регулярне резервне копіювання бази даних і можливість відновлення даних у випадку втрати або пошкодження.
