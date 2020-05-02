# Шаблоны для проверки заданий на курсе по анимациям

Здесь собираются markdown-шаблоны, которые ускоряют процесс проверки и помогают сохранять единый стиль и структуру проверок.

Базовые шаблоны первичной и вторичной проверки должны использоваться как основные комментарии в ревью. Эмодзи со значениями должны быть первыми символами во всех остальных комментариях - по ним мы можем легко отличать ошибки и советы друг от друга в длинных ревью.

Некоторые чеклисты также включают в себя важные оповещения для студентов. Так, например, в последнем задании про CSS есть напоминание о том, что нужно проверить все, что связано с CSS, прежде, чем переходить к следующим темам.


## Описание

Шаблоны поделены на файлы, начинающиеся с цифр (для основных файлов) либо с буквы и номера задания (для чеклистов), и лежат в одной директории, чтобы было удобно получать их содержимое через `cat`. В особенности это касается базовых шаблонов и критериев проверки.

Переносы строк могут ломаться при просмотре файлов в репозитории, но должны нормально работать в комментариях при code review.


## Обозначения в шаблонах

:red_circle: - Нужно обязательно исправить (грубые ошибки, несоответствия обязательным критериям).

:point_up: - Нужно подумать над этим, принять к сведению (мелкие недочеты, советы и.т.д.).

:watch: - Нужно подождать (что-то пошло не так, бот сломался, нужен ответ куратора и.т.д.).

:heavy_check_mark: - Задание принято.

:x: - Задание не принято.

:+1: - "Молодец".

:large_blue_diamond: - Важное сообщение (не упоминается в обозначениях в шаблонах, чтобы сразу бросалось в глаза).

