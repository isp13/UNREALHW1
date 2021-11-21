# Домашняя работа 1, UE4
3D платформер бесконечный раннер

**Концепция**

* ***Платформа***: Windows
* ***Технологии***: Unreal Engine 4.26.2, Blueprints
* ***Язык***: Английский
* ***Аудитория***:  Целевая аудитория
* ***Жанр***: 3D платформер
* ***Рейтинг***:  PEGI 3
* Singleplayer
* ***Время игры***: 10 мин+
* ***Основная механика***: Бесконечно бежать вперед так далеко, как только сможете
* ***Цель***: Достичь высокого результата
 
**Целевая аудитория**
Ориентирована в первую очередь на казуальных игроков разных возрастов, которые предпочитают играть в простые игры, чтобы убить время. 

**Игровой характер**

Игровая механика и управление
Управление:
  * Перемещение актера: Клавиши WASD.
  * Камера/поворот: Мышь (перемещение мыши для поворота камеры)
  * Прыжки: Пробел- чтобы прыгнуть выше  необходимо удерживать клавишу
Игровая механика:
  * Игрок может собирать бонусы в виде мячиков, чтобы получить более высокий результат.
  * Игрок должен избегать падений и столкновений с препятствиями.
  * Собирая бонусы, получайте баффы и быстрее набирайте очки
 
**Интерфейс**

HUD:
  * Счетчик очков

**Игровая карта**
Персонаж появляется в начале прохождения с различными препятствиями
В соответствии с пользовательским вводом персонаж может выполнять движения
При падении или столкновении с медным объектом игра перезапускается (game over)
Сбор бонусов изменяет условия игры на определенное время:
  * Бонус неуязвимости позволяет персонажу проходить сквозь медные объекты. 
  * Бонус "Замедление" замедляет движущиеся объекты 

**Дизайн уровня**
Игрок имеет 0 очков.
Игрок появляется на процедурно сгенерированном бесконечном пути с препятствиями.
Перед игроком случайным образом появляются платформы с движущимися препятствиями, бонусами, ускорителями, стенами и зазорами.
Можно породить два типа ускорителей: неуязвимость (позволяет проходить сквозь стены) и замедление (замедляет все движущиеся объекты).

**Баланс**

  * Скорость игрока: 800
  * Максимальная высота прыжка игрока: 300
  * Эффект гравитации на игрока: x2
  * Скорость передвижения препятствий варьируется по сложности
  * Медленное ускорение препятствий: 1 очко за ускорение
  * Время усиления неуязвимости: 8 - 3 (-1 за уровень сложности)
  * Время медленного форсирования: 12 - 4,5 (время форсирования непобедимости х1,5)
  * Бонусы за платформу: 0 - 2 (случайным образом)
  * Увеличение сложности по количеству очков: 100/200/400/800/1600

**Литература и источники туториалов**
* https://docs.unrealengine.com/4.27/en-US/
* https://www.youtube.com/watch?v=yS-yQfo0lc0&list=PLZlv_N0_O1gbY4FN8pZuEPVC9PzQThNn1&ab_channel=UnrealEngine


