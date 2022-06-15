# Fntastic
job test work - craft ui
<hr>

FIGMA:
[link](https://www.figma.com/file/kLwd1d6BBuPT3XuAlNsfCH/The-Day-Before---Craft-UI?node-id=70%3A3029)

FIGMA PROTOTYPE:
[link](https://www.figma.com/proto/kLwd1d6BBuPT3XuAlNsfCH/The-Day-Before---Craft-UI?page-id=20%3A1685&node-id=44%3A504&viewport=790%2C525%2C0.57&scaling=min-zoom&starting-point-node-id=44%3A504)

**Craft animation - кликабельная первая карточка (AID KIT)**

<hr>

## Задача:
- Создание UI фрейма крафта


## Вводные:


#### Референсы:
- The Last Of Us Part 2
- Tom Clancy’s The Division®2

#### Входные данные для разработки:
- Фрейм не должен занимать весь экран пользователя
- - В игре происходит постоянное движение и нет пауз, потому нельзя ограничивать обзор пользователя. Это может негативно повлиять на пользовательский опыт. (Внезапная смерть пользователя из-за нападения врагов, внутриигровых механик или других активностей)

- Интерфейс должен быть максимально минималистичным.
- - Задача визуального интерфейса быстро и доступно донести до юзера механики крафта, описания.

## Разработка:

Интерфейс разделяем на 3 равные части и выделяем правую область для отображения фрейма. Чтобы постараться дать пользователю больше обзора.

![image](https://user-images.githubusercontent.com/32073752/173785137-dacf93fa-1cf6-45be-b9e5-a6ca67fce89d.png)


На основе референсов и вводных данных я проработал пункты, которые нужны для отображения Craft UI:

![ux схема](https://user-images.githubusercontent.com/32073752/173786670-8c35afeb-2641-4fb9-8458-48484653440f.png)


#### Фрейм

![image](https://user-images.githubusercontent.com/107551907/173824584-c08a42d2-cfea-459e-ae24-5df7692e257a.png)

Состоит из HotKey клавиши и наименование фрейма

<hr>

#### Информация об объекте
![image](https://user-images.githubusercontent.com/107551907/173819818-9b8afef3-d020-46c6-b0be-549ac8ef5694.png)

1. Иконка категории объекта (визуальная кластеризация объектов. Ещё одно место для использования - Глоссарий, с базой всех предметов и их категориями)
2. Наименование объекта
3. Статуса объекта ( Недостаточно ресурсов / Доступно для крафта / Максимум )
4. Краткое описание объекта и его статусов
5. Ресурсы для крафта (текст + визуализация)

<hr>

####  Карточка объекта

![image](https://user-images.githubusercontent.com/107551907/173821682-f2ef3481-272f-4cd0-ba83-e751b1b83ebb.png)

1. Изображение объекта
2. Визуальное отображение количества доступных для хранения и создания объектов

Общее количество карточек в фрейме - [8]

<hr>

#### Доступные ресурсы

![image](https://user-images.githubusercontent.com/107551907/173823630-46449620-cbab-403e-a98a-f9cd1d66f027.png)

1. Иконка ресурса
2. Количество данного ресурса
3. При значении больше одной цифры, бандл сдвигается вправо

<hr>

#### Элементры управления

![image](https://user-images.githubusercontent.com/107551907/173823998-a416d4b3-fb82-4a2a-81cb-aef4855e8b79.png)


Состоит из трех вариантов состояний

1. HotKey клавиша + дублирование иконкой
2. HotKey клавиша
3. Hotkey клавиша с треугольником, действие - удержание клавиши

<hr>

## Итог:

![image](https://user-images.githubusercontent.com/32073752/173809776-82b98f39-11ab-4b20-99c0-eebf2c7f0f05.png)

#### Активация крафта:

![gif](https://im5.ezgif.com/tmp/ezgif-5-b7d6eae7b1.gif)

#### Тултипы ресурсов:

![gif](https://im5.ezgif.com/tmp/ezgif-5-87b3551526.gif)

#### Ховер эффект карточек

![gif](https://im5.ezgif.com/tmp/ezgif-5-f01399df59.gif)


Source:

![image](https://user-images.githubusercontent.com/107551907/173827236-ed086403-809f-4d06-96d3-2f0a81d6f746.png)

[stock.zip](https://github.com/iseenix/fntastic/files/8909278/stock.zip)


