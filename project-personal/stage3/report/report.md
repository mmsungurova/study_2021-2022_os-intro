---
## Front matter
title: "Пресональный проект ШАГ №3"
subtitle: 
author: "Сунгурова Мариян Мухсиновна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: false # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Добавить к сайту достижения. Сделать пост по прошедшей неделе. Добавить пост на тему по выбору.

# Задание

Добавить к сайту достижения.

    Список достижений.
        Добавить информацию о навыках (Skills).
        Добавить информацию об опыте (Experience).
        Добавить информацию о достижениях (Accomplishments).
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
        Легковесные языки разметки.
        Языки разметки. LaTeX.
        Язык разметки Markdown.


# Теоретическое введение

Сайт, или веб-сайт, также веб-узел, — одна или несколько логически связанных между собой веб-страниц; также место расположения контента сервера. Обычно сайт в Интернете представляет собой массив связанных данных, имеющий уникальный адрес и воспринимаемый пользователями как единое целое.

# Выполнение лабораторной работы

1. Добавить к сайту достижения.


- Добавить инфромацию о навыках(рис. [-@fig:001])

![Скриншот терминала](image/рис4.png){ #fig:001 width=70% }

- Добавить инфромацию об опыте (рис. [-@fig:002])

![Скриншот терминала](image/рис2.png){ #fig:002 width=70% }

- Добавить инфромацию о достижениях (рис. [-@fig:003])

![Скриншот терминала](image/рис3.png){ #fig:003 width=70% }

2. Сделать пост по прошедшей неделе. (рис. [-@fig:004])

![Скриншот](image/рис5.png){ #fig:004 width=70% }


2.  Добавить пост на тему по выбору. (рис. [-@fig:005])


![Скриншот терминала](image/рис6.png){ #fig:005 width=70% }


# Выводы

В процессе выполнения данного шага я добавила к сайту достижения, сделала пост по прошедшей неделе, добавила пост на тему по выбору.


# Список литературы{.unnumbered}

::: {#refs}
:::---

