# Border - Барьер мира для PocketMine-MP

[![PMMP Version](https://img.shields.io/badge/PocketMine-5.0.0+-blue.svg)](https://github.com/pmmp/PocketMine-MP)
[![NG Support](https://img.shields.io/badge/NetherGamesMC-1.20--1.21.93-green.svg)](https://github.com/NetherGamesMC/PocketMine-MP)

Плагин добавляет барьер, при входе в который игрока будет откидывать

## Установка
1. Скачайте `Border.phar`
2. Поместите в папку `plugins/`
3. Перезапустите сервер

*Для DevTools:*
1. Поместите `Border.zip` в `plugins/`
2. Разархивируйте
3. Перезагрузите сервер

## Использование
При входе в барьер, будет отбрасывать игрока и не давать пройти дальше, также в чат будет выводится сообщение, если в конфиге оно не отключено

Настройки в `config.yml`:
```yaml
min_x: -3500 # границы
max_x: 3500
min_z: -3500
max_z: 3500
msg: true # включить или отключить вывод сообщения в чат
msg_: §cВы вышли за границы мира! # сообщение при выходе за барьер"
