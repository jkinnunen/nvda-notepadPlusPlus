# Дополнение Notepad++ для NVDA #

Это дополнение улучшает доступность Notepad++. Notepad++ - это текстовый редактор для Windows, который имеет ряд возможностей. Вы можете узнать больше о нём на <https://notepad-plus-plus.org/>
Оригинальное дополнение было написано Дереком Римером и Тууккой Оджалой. Позже оно получило возможности, которые добавили Robert Hänggi и Andre9642.

## Возможности:

### Поддержка закладок

Notepad++ позволяет устанавливать закладки в тексте.
Закладка позволяет вам быстро перейти к определённому  расположению в редакторе из любого места.
Чтобы установить закладку, в строке, которую вы хотите заложить, нажмите control + f2.
Затем, когда вы захотите вернуться к этой закладки, нажмите f2 для перехода к следующей закладки, или shift + f2 для перехода к предыдущей.
Вы можете установить столько закладок, сколько захотите.

### Объявление максимальной длины строки

Notepad++ имеет линейку, используемую для проверки длины строки. Однако эта функция
недоступна для незрячих пользователей, поэтому это дополнение имеет звуковой индикатор, который подаёт звуковой сигнал, когда пользователь достигает максимальной длины строки.
Чтобы включить эту функцию, сначала запустите Notepad++, затем войдите в меню NVDA и выберите категорию Notepad++ в меню настроек.
Установите флажок " Включить индикатор длины строки " и изменяйте по мере необходимости максимальное количество символов.
Когда эта функция включена, вы услышите звуковой сигнал при прокрутке слишком длинной строки или достижения символов, которые превышают максимальную  длину. Как вариант, вы можете нажать NVDA + g, чтобы перейти к первому символу переполнения в активной строке.

### Переход к соответствующей скобке

В Notepad++ можно перейти к соответствующей скобке, нажав control + b. Для перемещения вы должны находиться на один символ внутри скобки, которую вы хотите сравнить. Когда вы нажмёте эту команду, NVDA прочитает строку, на которую вы перешли, а если строка состоит только из скобки, она прочитает строки под и над скобкой, чтобы вы могли понять контекст.


### Автозаполнение

Функционал автозаполнения в Notepad++ изначально недоступен. Автозаполнение имеет ряд проблем, среди которых - его показ в плавающем окне. Чтобы сделать этот функционал доступным, нужно сделать три вещи.

1. когда появляется предложение автозаполнения, раздастся свист. Обратный звук звучит, когда предложения исчезают.
2. нажмите стрелку вниз или вверх, чтобы прочитать следующий / предыдущий предложенный текст.
3. предлагаемый текст произносится по мере появления.

Обратите внимание: весь текст  также показывается шрифтом Брайля, если подключен
Брайлевский дисплей. Эта функция экспериментальная, не стесняйтесь сообщать, если у вас с ней возникают проблемы.

### Пошаговый поиск

Одна из самых интересных особенностей Notepad++  возможность использования пошагового поиска.
Пошаговый поиск-это режим поиска, в котором вы ищете текстовую фразу, вводя её в поле редактирования, а документ прокручивается, чтобы показать результат поиска в реальном времени. Он также подчеркивает соответствующий текст.
Программа также показывает, сколько совпадений было обнаружено. Есть кнопки для перехода к следующему и предыдущему совпадению.
При вводе NVDA будет объявлять строку текста, в котором Notepad++ обнаружил результат поиска. NVDA также сообщит о количестве совпадений, но только если количество совпадений изменилось.
Когда вы найдёте нужную строку текста, просто нажмите клавишу escape, и эта строка текста будет под вашим курсором.

Чтобы запустить этот диалог, выберите пошаговый поиск в меню поиска или нажмите alt + control + I.

### Уведомление о текущей строке

Если вы нажмёте nvda + shift + \ (обратная косая черта) в любой момент, появится
сообщение о следующем:

* номер строки
* номер колонки, то есть насколько символов Вы  продвинулись по строке.
* размер выделения (количество символов, выделенных по горизонтали, а затем количество символов, выделенных по вертикали, что образует прямоугольник). Эта информация сообщается только в случае необходимости.


### Поддержка функции предварительного / последующего поиска

Первоначально, если вы нажмете Control+f, откроется диалог поиска.
Если здесь ввести текст и нажать Enter, текст в окне будет выделен, а документ будет перемещён к следующему результату поиска.
В Notepad++ вы можете нажать f3 или shift + f3, чтобы повторить поиск в прямом или обратном направлении соответственно.
NVDA прочитает как текущую строку, так и выделение в строке, представляющей найденный текст.

## Пользовательские сочетания клавиш Notepad++

Ожидается, что это дополнение для Notepad++ используется со стандартными сочетаниями клавиш.
Если это не так, пожалуйста, измените
клавиатурные команды этого приложения, чтобы
они отображали ваши команды Notepad++, если
это необходимо в диалоговом окне жестов ввода NVDA.
Все команды приложения расположены в разделе Notepad++.