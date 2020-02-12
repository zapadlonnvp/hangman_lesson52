# игра "Виселица" 
описание игры: https://ru.wikipedia.org/wiki/Виселица_(игра)

Программа написана на языке Ruby.

Новые слова для игры добавляются в файл `/data/words.txt`

При запуске выбирается случайное слово, у игрока есть 7 попыток, чтобы его угадать по буквам. 

После каждой неудачной попытки компьютер дорисовывает элемент виселицы. 

Буквы "Е" и "Ё", "И" и "Й" в данной реализации программы для компьютера одинаковы. "Ъ" и "Ь" - разные :)

Помимо кода самой игры, демонстрируются возможности гема `Colorize` (https://github.com/fazibear/colorize) 

Для запуска выполнить `bundle install && bundle exec ruby main.rb`
