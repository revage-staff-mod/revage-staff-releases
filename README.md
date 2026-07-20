# Revage Staff — Releases

Публичный канал раздачи мода **Revage Staff**. Исходники — в приватном репозитории.

## Установка
1. Скачай последний `.jar` со вкладки [Releases](https://github.com/revage-staff-mod/revage-staff-releases/releases/latest).
2. Положи в `.minecraft/mods` (нужны Fabric Loader + Fabric API, Minecraft 1.21.11).

## Как выпускать обновление
1. В приватном репо подними `mod_version` в `gradle.properties`, собери: `./gradlew build`.
2. Создай здесь новый Release с тегом `vX.Y.Z`, прикрепи собранный `.jar`.
3. Обнови `version` в `version.json` на ту же версию — мод сам сообщит игрокам в чат.
