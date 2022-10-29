# CI/CD workflow for YAMDB

Проект настройки workflow CI/CD для приложения [YAMDB](https://github.com/vavilovnv/api_yamdb) при помощи GitHub actions.

Реализованы:
- автоматический запуск тестов flake8,
- обновление образа на Docker Hub,
- автоматический деплой на сервер при каждом пуше в главную ветку репозитария,
- отправка уведомления об успешном выполнении в телеграм-бот [homework_bot](https://github.com/vavilovnv/homework_bot).

[![workflow](https://github.com/vavilovnv/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg?branch=master)](https://github.com/vavilovnv/yamdb_final/actions/workflows/yamdb_workflow.yml) ![Python](https://img.shields.io/badge/-Python-blue) ![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=vavilovnv.yamdb_final)
