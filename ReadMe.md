# Инструкция по работе с Git

## Что такое git?
**Git** - это наиболее популярное реализация распределенной системы контроля версий. Самая популярная реализация **git** - это [github](https://github.com/)

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Для этого необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминале с папкой написать команду *git init*.

### Добавление файла к коммиту
Для добавления файла к будущему коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

### Создание коммита
Для создания коммита используется команда *git commit*. Для этого в терминале с папкой репозиторием необходимо написать *git commit -m <сообщение коммиту>*. Сообщение к коммиту писать ***О    бязательно!!!***.

## Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого в терминале с папкой-репозитория необходимо написать *git log*.

## Перемещение между коммитами
Для перемещения на предыдущие коммиты используется команда *checkout*. Для этого необходимо в журнале изменений, как показано в предыдущей части, найти необходимый коммит и его номер. После чего в терминале с папкой-репозиторием написать команду *git checkout <номер коммита>*. После применения этой команды вы попадете в состояние *Deteched head*, котором никакие изменения фиксироваться не будут. Для вохврата в обычное состояние необходимо написать команду *git checkout master*.

## Ветки в git

## Слияние веток и разрешение конфликтов

## Удаление веток

##
