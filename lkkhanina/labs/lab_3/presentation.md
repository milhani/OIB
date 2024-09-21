---
## Front matter
lang: ru-RU
title: Презентация к лабораторной работе №3
author: Ханина Людмила Константиновна
group: НПМбд-02-21

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

# Презентация к лабораторной работе №3

# Цель работы

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей.

# Выполнение работы

## Добавление пользователя guest2

![Добавление нового пользователя](image/1.png)

## Команды pwd, whoami, groups guest, id -Gn <имя пользователя> и id -G <имя пользователя>

![Информация о guest](image/2.png)

![Информация о guest2](image/3.png)

## Команда cat /etc/group

![Команда cat /etc/group](image/4.png)

## Регистрация Пользователя guest2 в группе guest

![Команда newgrp](image/5.png)

## Изменили права директории /home/guest

![Команда cat /etc/passwd](image/6.png)

# Вывод 

В ходе выполнения лабораторной работы №3 я получил практические навыки работы в консоли с атрибутами файлов для групп пользователей.
