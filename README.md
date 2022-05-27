# Локализация Star Citizen на русский язык (с сохранением оригинальных английских названий)
## UPD 27.05.2022: Локализация работает в обход EAC, обратите внимание на апдейты для каждой из утилит. [Подробнее как оно работает](#eac-about)
### Внимание! Все действия Вы выполняете на свой страх и риск. Использование локализации, на данный момент, нарушает лицензионное соглашение с разработчиками игры CIG. Надеемся, что CIG в скором времени разберутся с античитом и добавят локализацию в белый список.

### CIG просто меееееедленныееееее :/ Пнуть их можно (нужно!) тут: [https://robertsspaceindustries.com/spectrum/community/SC/forum/3/thread/any-update-on-the-mod-approval-program](https://robertsspaceindustries.com/spectrum/community/SC/forum/3/thread/any-update-on-the-mod-approval-program)



[![Latest Release Version](https://img.shields.io/github/release/budukratok/SC_not_so_ru?sort=date&label=Последняя%20версия)](https://github.com/budukratok/SC_not_so_ru/releases/latest)
[![Latest Release Downloads](https://img.shields.io/github/downloads/budukratok/SC_not_so_ru/latest/total?label=Скачиваний%20последней%20версии*)](https://github.com/budukratok/SC_not_so_ru/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/budukratok/SC_not_so_ru/total.svg?label=Скачиваний%20всего*)](https://github.com/budukratok/SC_not_so_ru/releases) 

Эта модификация добавляет поддержку русского языка в Star Citizen.
Создана силами сообщества "Star Citizen на русском" и является параллельной веткой основной полной локализации https://github.com/n1ghter/StarCitizenRu


Если вы нашли какие-то ошибки в переводе просьба обращатся в дискорд сообщества: https://discord.gg/8U45k2CkE4

## Установка

### Приложения для установки и обновления

* Star Citizen Tools от h0use [описание](https://github.com/h0useRus/StarCitizen) | [скачать](https://github.com/h0useRus/StarCitizen/releases/latest) | [как включить](#sctools-settings)
* Star Citizen Helper от Shin0by [описание](https://github.com/Shin0by/StarCitizen-Helper) | [скачать](https://github.com/Shin0by/StarCitizen-Helper/releases/latest) | [как включить](#schelper-settings)

<a name="sctools-settings"></a>
## Как включить чтобы всё работало в приложении Star Citizen Tools от h0useRus
Зайти в настройки локализации:

![Клик по "Локализация LIVE"](/.github/images/ZDXMYFMXKNUGIHN.png)

В новом окне зайти в "Управл.":

![Клик по "Управл."](/.github/images/HIFXDFZNOLKXOGW.png)

Во вкладке "Стандартные" выбрать "Russian Community (без названий)" и нажать "Добавить":

![Клик по "Добавить"](/.github/images/RSCUUMVOTAMZRQO.png)

Выбрать "Russian Community (без названий)" в списке:

![Выбор в списке](/.github/images/PWLOHULCORZQJAO.png)

Нажать "Обновить"

![Нажатие "Обновить"](/.github/images/IXQNVCENNBLULXR.png)

Если локализация выключена, то нужно будет ещё нажать "Включить локализацию". После этого при входе в игру всё должно быть на русском. Программу можно закрывать (**ВАЖНО**: запускайте её время от времени, чтобы обновлять версию локализации. Особено это важно в пару дней после выхода нового патча.).

При желании - можно отключить перевод интерфейсов внутри корабля (чтобы стало VTOL вместо СВВП, ESP вместо УТУ и т.д.).
Для этого нужно выбрать язык локализации "russiannohud":

![russiannohud](/.github/images/GIXAVOLAZBGPNCU.png)


Теперь при запуске программы достаточно будет на главном экране нажимать "Проверка обновлений", чтобы постоянно оставаться на актуальной версии локализации:

![Проверка обновлений](/.github/images/WMNFSPIDULLIXNV.png)

### UPD 27.05.2022:
Для запуска в обход EAC, чтобы локализация заработала, нужно нажать на кнопку "Постоянная вселенная" (если кнопки нет - нужно обновить SCTools) и следовать инструкциям, чтобы сохранить токен. [Подробнее описано в апдейте от Shin0by](#eac-about)
 

<a name="schelper-settings"></a>
## Как включить чтобы всё работало в приложении Star Citizen Helper от Shin0by 

![Инструкция](/.github/images/nohud_example.png)

<a name="eac-about"></a>
### UPD 27.05.2022:
Теперь программа автоматически сохраняет игровой ключ (далее Токен), при запуске игры штатными методами (с помощью игрового лаунчера). Этот Токен используется для последующего запуска игры в обход игрового лаунчера и EAC, что позволяет включить локализацию. Данное решение является временным, мы надеемся избавиться от него после того, как локализация будет добавлена в белый список EAC.
Вкладка "Модификация" - добавлена кнопка "Запуск игры".
Кнопка "Запуск игры" запускает игру с локализацией, используя ранее сохраненный ключ. Для запуска игры, должна быть загружена, установлена и включена последняя версия локализации.
Внимание! Все действия со StarCitizen Helper Вы выполняете на свой страх и риск. Использование локализации, на данный момент, нарушает лицензионное соглашение с разработчиками игры CIG.



### Если нравится питон и хочется всё вручную

Для установки и обновления скачанной локализации вы можете использовать напрямую git и Python скрипты. Подробнее по ссылке:
* https://github.com/defterai/StarCitizenModding

### Чтобы помочь поиску в гугле:
star citizen локализация, star citizen русская локализация, star citizen локализация на русском, star citizen перевод, star citizen русский перевод, star citizen перевод на русский, star citizen русский, star citizen русский язык, star citizen язык русский, star citizen на русском, star citizen русификатор, star citizen ru, star citizen ру, star citizen,

локализация star citizen, русская локализация star citizen, локализация на русском star citizen, перевод star citizen, русский перевод star citizen, перевод на русский star citizen, русский star citizen, русский язык star citizen, язык русский star citizen, на русском star citizen, русификатор star citizen, ru star citizen, citizen русский,

стар ситизен локализация, стар ситизен русская локализация, стар ситизен локализация на русском, стар ситизен перевод, стар ситизен русский перевод, стар ситизен перевод на русский, стар ситизен русский, стар ситизен русский язык, стар ситизен язык русский, стар ситизен на русском, стар ситизен русификатор, стар ситизен ru, стар ситизен ру, стар ситизен,

локализация стар ситизен, русская локализация стар ситизен, локализация на русском стар ситизен, перевод стар ситизен, русский перевод стар ситизен, перевод на русский стар ситизен, русский стар ситизен, русский язык стар ситизен, язык русский стар ситизен, на русском стар ситизен, русификатор стар ситизен, ru стар ситизен, ситизен русский,
