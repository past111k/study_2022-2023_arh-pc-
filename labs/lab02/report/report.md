---
## Front matter
title: "Лабораторая работа №2"
subtitle: "Архитектура вычислительных систем "
author: "Кочарян Никита Робертович"

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
lot: true # List of tables
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
  
	Изучить идеологию и применение средств контроля версий.
Приобрести практические навыки по работе с системой git.
  
# Задание

1.	Создайте отчет по выполнению лабораторной работы в соответствующем
каталоге рабочего пространства (labs>lab03>report).
2.	Скопируйте отчеты по выполнению предыдущих лабораторных работ в
соответствующие каталоги созданного рабочего пространства.
3.	Загрузите файлы на github.

# Теоретическое введение

# Выполнение лабораторной работы

1.	Сначала сделаем предварительную конфигурацию git. Откроем терминал и введем следующие команды, указав свое имя и email.

![Предварительная конфинурация git](image/2.1.png){ #fig:001 width=90% }

2.	Настроим utf-8 в выводе сообщений git.

![Настройка utf-8 ](image/2.2.png){ #fig:002 width=90% }

3.	Зададим имя начальной ветки.

![Задаем имя начальной ветки](image/2.3.png){ #fig:003 width=90% }

4.	Параметр autocrlf

![Параметр autocrlf](image/2.4.png){ #fig:004 width=90% }

5.	Параметр safecrlf.

![Параметр safecrlf](image/2.5.png){ #fig:005 width=90% }

6.	Создаем пару ключей.

![Создание ключей](image/2.6.png{ #fig:006 width=90% }

7.	Далее необходимо загрузить сгенерённый открытый ключ. Для этого зайдем на сайт github, копируем ключ из локальной консоли в буфер обмена.

![Загрузка ключа на github](image/2.7.png){ #fig:007 width=90% }

8.	Создадим каталог для предмета «Архитектура компьютера».

![Создание каталога Архитектура компьютера](image/2.8.png){ #fig:008 width=90% }

9.	Перейдем на станицу репозитория с шаблоном курса. В открывшемся окне задаем имя репозитория(из-за невнимательности забыл заскринить страницу с задавания имени репозитория).

![Задаем имя репозитория](image/2.9.png){ #fig:009 width=90% }

10.	Откроем терминал и перей дем в каталог курса.

![Переход в каталог курса](image/2.10.png){ #fig:010 width=90% }

11.	Клонируем созданный репозиторий.

![Клонирование репозитория](image/2.11.png){ #fig:011 width=90% }

12.	Перейдем в каталог курса и удалим лишние файлы.

![Удаление лишних файлов](image/2.12.png){ #fig:012 width=90% }

13.	Создадим необходимые каталоги.

![Создание каталогов](image/2.13.png){ #fig:013 width=90% }

14.	Отправляем файлы на сервер.

![Отправка файлов на сервер](image/2.14.png){ #fig:014 width=90% }

15.	Проверим правильность создания иерархии рабочего пространства в локальном репозитории и на странице github.

![Проверка правильности созданной иерархии рабочего пространства](image/2.15.png){ #fig:015 width=90% }

# Выводы

Я изучил идеологию и применение средств контроля версий, а также приобрел практические навыки по работе с системой git.

# Список литературы{.unnumbered}

::: {#refs}
:::
