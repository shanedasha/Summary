# **План тестирования**

### I.Перечень автоматизируемых сценариев
* E2E тест: полистать все страницу профессии до формы записи и заполнить ее, нажать записаться.
* Е2Е тест:нажать первую из двух кнопок "Записаться" на странице профессии, заполнить форму записи, нажать записаться.
* Е2Е тест:нажать вторую из двух кнопок "Записаться" на странице профессии,  заполнить форму записи, нажать записаться.
* E2E тест:нажать на "каталог курсов", выбрать любой курс из списка, пролистать все страницу до  формы записи и заполнить ее, нажать записаться.
* E2E тест:нажать на интерактивный кружок в начале страницы с выбором уровня курсов, выбрать любой курс из списка, пролистать все страницу до  формы записи и заполнить ее, нажать записаться.
* UI тест: заполнить форму валидными данными, нажать записаться.
* Позитивные тесты на поле "телефон".
* Негативные тесты на поле "телефон".
* Позитивные тесты на поле "имя".
* Негативные тесты на поле "имя".
### II.Перечень используемых инструментов с обоснованием выбора
* Selenium, Selenide для автоматизации.
* JUnit для возможности создания самих тестов.
* Gradle для управления нужными зависимостями и для отчетов.
### III.Перечень необходимых разрешений/данных/доступов
Нужны данные для поля "имя" и "телефон". Их можно генерировать с помощью библиотеки faker.
### IV.Перечень и описание возможных рисков при автоматизации
* Если неверно выбрать инструмент для тестирования, можно попасть в зависимость от технологий и специалистов.
* Скрипты могут находить «ложные» дефекты – их  надо проверять вручную.
### V.Перечень необходимых специалистов для автоматизации
* Инженер по автоматизированному тестированию 
* DevOps (помогают настроить тестовое окружение)
### VI.Интервальная оценка с учётом рисков (в часах)
* 3 часа.
