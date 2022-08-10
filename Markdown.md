# Инструкция по работе с Git


## Создание репозитория

1. С нуля -- Создать новый локальный репозиторий

   $ git init [project name]

2. Скачать с существующего репозитория

   $ git clone my_url

## Отслеживание репозитория

* Просмотреть список новых или измененных файлов, которые еще не закомитены

  $ git status

- Показать изменения в файлах, которые еще не поставлены

   $ git diff

+ Показать полную историю изменений
  
  $ git log

## Работа с ветками

* Показать все локальные ветки

   $ git branch

+ Создание новой ветки с именем new_branch

   $ git branch new_branch

- Переключится к ветке my_branch и обновить рабочую директорию

   $ git checkout my_branch

* Объединить branch_a в branch_b

  $ git checkout branch_b
  
  $ git merge brabch_a

  ## Изменения

  > Индексировать все файлы готовые к комиту
  
    $ git add
  
  > Зафиксировать индексированные файлы с комментарием в историю 

    $ git commit -m "commit message"

### Ссылка
[Встроенная ссылка](https://ru.wikipedia.org/wiki/Markdown)


![Picture](//placehold.it/150x100 "Можно задать title")

## Таблицы

First Header | Second Header
-------------|--------------
Content Cell | Content Cell
Content Cell | Content Cell
