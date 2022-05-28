---
## Front matter
lang: ru-RU
title: Лабораторная работа 11
author: |
  М Шариф Камран, НПИ-02-21, 1032217625
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 20 May, 2022

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Цель и задачи

Изучить основы программирования в оболочке ОС UNIX. Научится писать более
сложные командные файлы с использованием логических управляющих конструкций
и циклов.

## Задачи

Требуется написать 4 командных файла:

- принимает аргументы с командной строки и использует их для запуска `grep`
- запускает другую программу и получает ее код выхода
- создает файлы с названиями, имеющими номер в последовательности
- создает архив из файлов, которые обновлены меньше чем неделю назад

# Выполнение работы

## Программа для запуска `grep`

![image](https://user-images.githubusercontent.com/103488170/170822252-3b7566a8-5b80-4fcd-a6b0-00ac38a90459.png)


## Программа для проверки кода выхода программы

![image](https://user-images.githubusercontent.com/103488170/170822262-a7340080-bb45-4bd6-a181-c9e13707dd13.png)


## Программа для создания файлов

![image](https://user-images.githubusercontent.com/103488170/170822275-d86d2d34-0052-451f-b99b-f261e36f9f6d.png)


## Программа для создания архива

![image](https://user-images.githubusercontent.com/103488170/170822288-a8d5a826-75fa-405b-addb-925d7355b443.png)


# Заключение

Командные файлы -- это удобный способ писать программы в той же самой среде, в которой работает пользователь.

Используя четыре приведенных примера, можно комбинировать и решать более сложные задачи, не используя других языков программирования.
