<h1 align="center">--Weather-App--</h2>
<br>
<div align="center">

<div align="center">

![API](https://img.shields.io/badge/-API-009688?style=plastic&logo=fastAPI) ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=plastic&logo=HTML5) ![CSS](https://img.shields.io/badge/-CSS3-blue?style=plastic&logo=CSS3) ![JavaScript](https://img.shields.io/badge/-JavaScript-yellow?style=plastic&logo=JavaScript) ![Sass](https://img.shields.io/badge/-Sass-pink?style=plastic&logo=Sass) ![Webpack](https://img.shields.io/badge/-Webpack-8DD6F9?style=plastic&logo=Webpack) ![BABEL](https://img.shields.io/badge/-BABEL-F9DC3E?style=plastic&logo=BABEL) ![Gulp](https://img.shields.io/badge/-Gulp-CF4647?style=plastic&logo=Gulp)
</div>

<img src="https://file.modx.pro/files/7/1/e/71e9d5d262031be9f72008ce21b917a6.png" />

<h2 align="center">Описание</h2>

- Приложение Weather-App с использованием JavaScript/fetch для получения данных из API

<h2 align="center">Структура приложения</h2>
Приложение состоит из трех функциональных блоков:<br>

- Блок контроля
- Погода за сегодня
- Геолокационные данные

<h2 align="center">Описание функциональных блоков</h2>

### 1. Блок контроля

- динамическая строка поиска
- кнопка для переключения фоновой темы изображения

### 2. Погода за сегодня

- название населённого пункта,города, название страны
- текущая дата: день недели в коротком формате, число, месяц 
- анимация погоды
- изменение фонового изображения `DAY-NIGHT` в соответствии с часовым поясом стран
- температура в текущий промежуток времени
- описание погоды, ощущаемая температура (apparent temperature), скорость ветра(м/с), влажность(%), давление(мм)

### 3. Геолокационные данные

- координаты населённого пункта: долгота и широта (в градусах и минутах)
- определения местоположения 

<h2 align="center">Работа приложения</h2>

- Когда пользователь открывает приложение, все данные `UNKNOWN`
- Когда пользователь подтверждает определения местоположения, приложение относится к текущему местоположению пользователя
- Неподтверждение местоположения пользователя, выводит `USER DENIED GEOLOCATION`
- В строке поиска осуществляется поиск по населённому пункту
- Когда пользователь вводит  неверное название населённого пункта, приложение `CITY NOT FOUND`
- Фоновое изображение `DAY-NIGHT` изменяется в соответствии с часовым поясом стран при обновлении содержания страницы 
- При клике по кнопке изменяется фоновая тема изображения в блоке контроля 
- Местоположения пользователя сохраняется в local storage. 

<h2 align="center">Технические требования</h2>

- для использования и теста функционала приложения Weather-App, его нужно скачать <a href="https://github.com/binkovskyi94/Weather-App"><img src="https://img.shields.io/badge/-downloads-green.svg?style=plastic&logo="></a> или клонировать репозиторий `https://github.com/binkovskyi94/Weather-App.git`
- приложение корректно работает в последней версии Chrome, Chrome Dev, Opera, Mozila
- разрешается использовать jQuery или другие JS библиолеки только в качесте подключаемой зависимости для UI библиотек. Использование jQuery и JS библиотек в основном коде приложения не допускается
- использование Angular / React / Vue допускается только по личной договорённости с ментором

