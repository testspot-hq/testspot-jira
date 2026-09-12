# TestSpot for Jira

Панель TestSpot в задаче Jira: связанные тест-кейсы, прогоны и дефекты.

## Jira Data Center

Скачайте плагин из [Releases](https://github.com/testspot-hq/testspot-jira/releases/latest):

- `testspot-jira-panel-0.1.0.jar` — плагин для загрузки в Jira.
- `testspot-jira-panel-0.1.0-dc.zip` — плагин, инструкция и контрольная сумма.
- `SHA256SUMS` — SHA-256 опубликованных файлов.

Установите JAR через **Administration → Manage apps → Upload app**, затем настройте адрес TestSpot и общий секрет по [инструкции](INSTALL.md).

Для работы нужен развёрнутый TestSpot. Интерфейс панели загружается с вашего сервера TestSpot; JAR добавляет панель в Jira и подписывает контекст пользователя. Каждый пользователь подключает свою учётную запись TestSpot.

## Jira Cloud

Версия для Jira Cloud работает через Atlassian Forge. JAR из этого репозитория предназначен для Data Center; способ подключения Cloud согласуется при настройке вашего TestSpot.

## Обновления

Новая версия DC-плагина устанавливается через **Upload app**. Изменения интерфейса панели поставляются с обновлениями TestSpot.

[TestSpot CLI](https://github.com/testspot-hq/testspot-cli) — загрузка результатов автотестов из CI.
