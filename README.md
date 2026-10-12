# Uptime Toolkit Marketplace

Локальный marketplace агентских плагинов. В нём доступен `uptime-toolkit` — набор рабочих процессов для разработки, ревью, документации и релизов Uptime App.

## Состав

- `plugins/uptime-toolkit` — исходный пакет плагина и его skills.
- `.agents/plugins/marketplace.json` — манифест marketplace, регистрирующий пакет по переносимому относительному пути.

## Подключение

Откройте этот репозиторий в Codex и используйте файл `.agents/plugins/marketplace.json` как локальный marketplace. Плагин имеет политику `AVAILABLE`, поэтому его можно установить по запросу из списка доступных плагинов.
