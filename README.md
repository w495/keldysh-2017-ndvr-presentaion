# Поиск нечётких дубликатов видео

## Что это

Презентация доклада «Поиск нечётких дубликатов видео»
на научном семинаре в Институте прикладной математики им. М. В. Келдыша Российской академии наук
21 декабря 2017 года.

Собранную версию презентации можно натий по ссылкам:
* https://www.researchgate.net/publication/322297857_keldysh-2017
* https://www.academia.edu/35597579/keldysh-2017

### О чём

Доклад посвящён поиску похожих видео. Введено понятие «нечетких дубликатов» видео. Нечетким дубликатом называют объект, частично совпадающий с другим объектом подобного класса. Рассмотрена актуальность проблемы поиска нечетких дубликатов видео. Построена обобщённая модель поиска по видео. Предложен метод поиска и сравнения нечетких дубликатов, который с помощью сегментации видео по временной оси, сводит задачу к поиску и сравнению временных рядов. Представлен декларативный язык потоковой фильтрации видео, с помощью которого реализована сегментации. Сформулирован алгоритм индексации и поиска нечётких дубликатов видео. Проведено сравнение с аналогами

The presentation focuses on finding of similar videos. The notion of «near-duplicates» is introduced. A near-duplicate is an object that approximates another object of the same class. The presentation contains near duplicate problem statement and a generalized model of the video search. Also a method of searching and comparing near duplicate videos is proposed. The method reduces near duplicate videos retrieval to time series indexation. This is achieved through a temporal video segmentation. Also a streaming video filtering declarative language is presented. It helps to implement a video segmentation. A final algorithm for near duplicate videos indexation and retrieval is formulated and compared with analogues. 


## Требования

* `make`;
* `XeLaTeX`;
* `beamer` (библиотека для `*TeX`);
* `tikz` (библиотека для `*TeX`);
* `polyglossia` (библиотека для `XeLaTeX`);
* ...

Если чего-то будет не хватать, то не трудно поставить
по мере надобности, или отключить в стилях (`./styles`).

### Шрифты

* `Times New Roman`;
* `Calibri`;
* `SansRoundedLightC`;
* `SansRoundedC`;
* `LMMono12`;

Используемые шрифты не прилагаются.

## Установка

### Глобальная

Для сборки установите тему `tvzavr` для `beamer`.
Она описана в `./styles/Pres/`. У меня темы ставятся в

    /usr/share/texlive/texmf-dist/tex/latex/beamer/themes/theme/

### Локальная

    make localthemes

## Сборка

    make all

## Структура

    .
    |-- src/    ## исходные коды презентации.
    |-- img/    ## изображения.
    `-- styles/ ## стили.
