# selenium-final-project

Решение финального задания курса «Автоматизация тестирования с помощью Selenium и Python» (Stepik).

Автотесты интернет-магазина http://selenium1py.pythonanywhere.com/, написанные по паттерну Page Object: страницы описаны в папке `pages/`, тесты — в файлах `test_*.py`.

## Запуск

Установка зависимостей (Python 3.11+, нужен установленный Chrome):

    pip install -r requirements.txt

Запуск тестов:

    pytest -v --tb=line --language=en

Запуск тестов, помеченных для проверки (`need_review`):

    pytest -v --tb=line --language=en -m need_review
