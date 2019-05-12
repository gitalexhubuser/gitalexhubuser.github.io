# [ER EasyRotation](http://easyrotation.pro)
Данная программа позволит вам использовать все прелести lua языка, в рамках игры World of Warcraft. Можно читерить на аренах, использовать аторотацию в PvE, или написать собственного аукцион бота. И все это в обход Blizzard Protect Code.
На данный момент у нас в наличии имеется достаточно ротаций на любой класс и спек.

## Гайд по использованию
Сразу же после установки, при первом запуске программа попросит ввести ваш ключ `который приобретается отдельно`.
Ключ хранится в реестре по адресу `HKEY_CURRENT_USER/System/ER`

Нажать кнопку `из папки scripts`

## Полезные ссылки
[1](https://projects.lukehaas.me/scrollify/examples/apple)

## Маркосы для проверки
```lua
print("123");
```
Сперва в самой игре, в чате вбейте
```lua
/run JumpOrAscendStart();
```
Обратите внимание это у нас `blizzard protected function`

Теперь вбиваем эту же команду, но уже в поле ввода скриптов самой программы `2-я вкладка ER`
```lua
/run JumpOrAscendStart();
```
Пример функции
```lua
JumpOrAscendStart();
```
```lua
--[[-----------------------------------------------
Раз в 3 сек.
--]]-----------------------------------------------
local function onUpdate(self, elapsed)
UpDate = 0;
local UpDate = UpDate + elapsed;
  if (UpDate > 3) then
    print("123")
  end
end
local f = CreateFrame("Frame")
f:SetScript("OnUpdate", onUpdate)
```

## предложение и ссылка
If you're working with Scrollify and having issues, please post your questions to [Stackoverflow](http://stackoverflow.com) and tag it with 'jquery-scrollify'.



## Часто задаваемые вопросы
- На каких версиях игры работает?

Только 3.3.5а 12340

- Смогу ли я активировать ключ на ещё одном своём устройстве?

Нет, т.к идёт привязка по железу!

- Где можно приобрести программу?


