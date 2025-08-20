<a id="2.2.0"></a>
# [2.2.0 - Поддержка KeenOS 4+](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.2.0) - 2025-08-20

- Добавлена поддержка KeenOS 4+
- Добавлена проверка версии KeenOS при установке и обновлении
- Обновлены основные скрипты
- Уменьшен размер бота
- Установка, обновление и удаление теперь идет через скрипт
- IP роутера вычисляется автоматически
- При обновлении через скрипт порты берутся из bot_config.py
- Добавлен список VPN в bot_config.py
- Поправлены скрипты для ключей trojan и v2ray
- Исправлена ошибка, если в имени VPN был дефис
- Проверена работа VPN на KeenOS 4+
- Добавлено сообщение перед перезагрузкой мостов
- Добавлено исправление при превышении списка > 4096 символов
- Добавлены информационные смайлы в меню

## What's Changed
* Update changelog for "2.1.9" by [@github-actions](https://github.com/github-actions) in [#13](https://github.com/keenetic-dev/bypass_keenetic/pull/13)
* Update README.md by [@znetworkx](https://github.com/znetworkx) in [#15](https://github.com/keenetic-dev/bypass_keenetic/pull/15)
* Update README.md by [@znetworkx](https://github.com/znetworkx) in [#16](https://github.com/keenetic-dev/bypass_keenetic/pull/16)
* Update README.md by [@znetworkx](https://github.com/znetworkx) in [#17](https://github.com/keenetic-dev/bypass_keenetic/pull/17)


**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.9...2.2.0


[Changes][2.2.0]


<a id="2.1.9"></a>
# [2.1.9 - fix vpn service, wireguard](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.1.9) - 2025-08-20

- *Исправлены ошибки в скриптах для VPN*
- *Протестирована и настроена работа с Wireguard*
- *Исправлены мелкие ошибки*
- *В бот добавлена информация `где брать ключи`*
- *Обновлено меню*
- *Добавлены реквизиты для доната*

**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.8...2.1.9

[Changes][2.1.9]


<a id="2.1.8"></a>
# [2.1.8 - fix update via bot, etc](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.1.8) - 2025-08-20

- Добавлено: вывод сообщений при обновлении
- Исправлены мелкие ошибки

## What's Changed
* Update changelog for "2.1.6" by [@github-actions](https://github.com/github-actions) in [#8](https://github.com/keenetic-dev/bypass_keenetic/pull/8)
* Update changelog for "2.1.7" by [@github-actions](https://github.com/github-actions) in [#9](https://github.com/keenetic-dev/bypass_keenetic/pull/9)


**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.7...2.1.8

[Changes][2.1.8]


<a id="2.1.7"></a>
# [2.1.7 - added update via bot](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.1.7) - 2025-08-20

- добавлено обновление через бот /update

**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.6...2.1.7

[Changes][2.1.7]


<a id="2.1.6"></a>
# [2.1.6 - fix check files exist](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.1.6) - 2025-08-20

- Добавлена проверка наличия файлов для vpn.

## What's Changed
* Update changelog for 2.1.1 by [@github-actions](https://github.com/github-actions) in [#4](https://github.com/keenetic-dev/bypass_keenetic/pull/4)
* 2.1.5 by [@znetworkx](https://github.com/znetworkx) in [ziwork/bypass_keenetic#5](https://github.com/ziwork/bypass_keenetic/pull/5)
* Update changelog for 2.1.5 by [@github-actions](https://github.com/github-actions) in [#7](https://github.com/keenetic-dev/bypass_keenetic/pull/7)

## New Contributors
* [@github-actions](https://github.com/github-actions) made their first contribution in [#4](https://github.com/keenetic-dev/bypass_keenetic/pull/4)

**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.5...2.1.6

[Changes][2.1.6]


<a id="2.1.5"></a>
# [2.1.5 - update bot, vpn service, etc](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.1.5) - 2025-08-20

- Добавлено меню сервис в бота
- Добавлена возможность перезагрузки мостов
- Добавлена возможность перезагрузки роутера
- Добавлена возможность просмотра обновлений
- Добавлена возможность вкл/выкл dns override
- Добавлена будущая возможность обновления через бот
- Доработан сервис VPN для более одного подключения
- Исправлены правила, из-за которых были отвалы TSMB и RCI API
- Доработан конфиг dnsmasq.conf
- Из установки убрано автоматическое получение ключей TOR
- Доработаны скрипты .sh
- Добавлен файл changelog.md
- Добавлена возможность выбора репозитория при установке

**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.1...2.1.5

[Changes][2.1.5]


<a id="2.1.1"></a>
# [2.1.1 - fix bot menu](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.1.1) - 2025-08-20

[#1](https://github.com/keenetic-dev/bypass_keenetic/issues/1) 2.1.1 - Изменено отображение меню добавления адресов в список, теперь компактно.

## What's Changed
* 2.1.0 - add VPN service, fix bugs by [@znetworkx](https://github.com/znetworkx) in [#1](https://github.com/keenetic-dev/bypass_keenetic/pull/1)

## New Contributors
* [@znetworkx](https://github.com/znetworkx) made their first contribution in [#1](https://github.com/keenetic-dev/bypass_keenetic/pull/1)

**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.0...2.1.1

[Changes][2.1.1]


<a id="2.1.0"></a>
# [2.1.0 - add VPN service, fix bugs](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.1.0) - 2025-08-20

[#8](https://github.com/keenetic-dev/bypass_keenetic/issues/8) 2.1.0
- Добавлена поддержка VPN
- Исправлены мелкие ошибки

**Full Changelog**: https://github.com/ziwork/bypass_keenetic/compare/2.0.2...2.1.0

[Changes][2.1.0]


<a id="2.0.2"></a>
# [2.0.2 - update bot, add v2ray, trojan vpn, etc](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.0.2) - 2025-08-20

### 2.0.2 - NEW BOT 

- update bot, version 2.0.2
- update scripts, fix syntax posix
- add v2ray, trojan service
- add help how to install new 2.0.0 version or update

**Full Changelog**: https://github.com/keenetic-dev/bypass_keenetic/compare/2.0.0...2.0.2

[Changes][2.0.2]


<a id="2.0.0"></a>
# [2.0.0 - first release bot 2.0](https://github.com/keenetic-dev/bypass_keenetic/releases/tag/2.0.0) - 2025-08-20

- Добавлены сервисы v2ray. trojan vpn
- обновлены скрипты

[Changes][2.0.0]


[2.2.0]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.9...2.2.0
[2.1.9]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.8...2.1.9
[2.1.8]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.7...2.1.8
[2.1.7]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.6...2.1.7
[2.1.6]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.5...2.1.6
[2.1.5]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.1...2.1.5
[2.1.1]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.1.0...2.1.1
[2.1.0]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.0.2...2.1.0
[2.0.2]: https://github.com/keenetic-dev/bypass_keenetic/compare/2.0.0...2.0.2
[2.0.0]: https://github.com/keenetic-dev/bypass_keenetic/tree/2.0.0

<!-- Generated by https://github.com/rhysd/changelog-from-release v3.9.0 -->
