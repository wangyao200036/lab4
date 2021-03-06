**РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**

**Факультет физико-математических и естественных наук**

**Кафедра прикладной информатики и теории вероятностей**

**ОТЧЕТ**

**по лабораторной работе № 4**

*[дисциплина: операценные системы]{.underline}*

[Студент: Ван Яо]{.underline}

Группа:НПмбд-02-21

**МОСКВА**

20 [22]{.underline} г.

1Цель работы

Приобретение практических навыков взаимодействия пользователя с системой
посредством командной строки

Указания к работе

Формат команды.：Общий формат команд можно представить следующим
образом:

Команда man.

![](media/image1.png){width="6.6875in" height="4.131944444444445in"}

Команда cd. Команда cd используется для перемещения по файловой системе
операционной системы типа Linux.

Формат команды: cd \[путь_к\_каталогу

![](media/image2.png){width="6.694444444444445in"
height="4.131944444444445in"}

Команда pwd. Для определения абсолютного пути к текущему каталогу
используется команда pwd (print working directory).

![](media/image3.png){width="6.0625in" height="1.7013888888888888in"}

Сокращения имён файлов

![](media/image4.png){width="6.020833333333333in"
height="2.3333333333333335in"}

Команда ls. Команда ls используется для просмотра содержимого каталога.
Формат команды: ls \[-опции\] \[путь

![](media/image5.png){width="4.388888888888889in"
height="0.6458333333333334in"}

. Для того, чтобы отобразить имена скрытых файлов, необходимо
использовать команду ls с опцией a: 1 ls --a

![](media/image6.png){width="3.7916666666666665in" height="0.6875in"}

Чтобы вывести на экран подробную информацию о файлах и каталогах,
необходимо использовать опцию l

![](media/image7.png){width="6.6875in" height="0.8888888888888888in"}

![](media/image8.png){width="6.6875in" height="2.4097222222222223in"}

Команда mkdir. Команда mkdir используется для создания каталогов. Формат
команды: mkdir имя_каталога1 \[имя_каталога2\...\]

![](media/image9.png){width="6.6875in" height="1.3263888888888888in"}

Для того чтобы создать каталог в определённом месте файловой системы,
должны быть правильно установлены права доступа.

![](media/image10.png){width="6.6875in" height="1.1736111111111112in"}

Интересны следующие опции: \--mode (или -m) --- установка атрибутов
доступа; \--parents (или -p)--- создание каталога вместе с родительскими
по отношению к нему каталогами. Атрибуты задаются в численной или
символьной нотации:

![](media/image11.png){width="6.694444444444445in"
height="0.3194444444444444in"}

Опция \--parents (краткая форма -p) позволяет создавать иерархическую
цепочку подкаталогов, создавая все промежуточные каталоги:

![](media/image12.png){width="6.229166666666667in"
height="0.4583333333333333in"}

Команда rm. Команда rm используется для удаления файлов и/или каталогов.
Формат команды: rm \[-опции\] \[файл\] Если требуется, чтобы выдавался
запрос подтверждения на удаление файла, то необходимо использовать опцию
i. Чтобы удалить каталог, содержащий файлы, нужно использовать опцию r.
Без указания этой опции команда не будет выполняться

![](media/image13.png){width="5.013888888888889in"
height="1.6041666666666667in"}

Команда history.

![](media/image14.png){width="4.958333333333333in"
height="3.1666666666666665in"}

Можно модифицировать команду из выведенного на экран списка при помощи
следующей конструкции:

!:s//

![](media/image15.png){width="6.6875in" height="1.1944444444444444in"}

Использование символа «;». Если требуется выполнить последовательно
несколько команд, записанный в одной строке, то для этого используется
символ точка с запятой Пример:

![](media/image16.png){width="6.6875in" height="0.8888888888888888in"}

3.Вывод:получил Приобретение практических навыков взаимодействия
пользователя с системой посредством командной строки.

4.1Терминал Linux предоставляет вам интерфейс, в котором вы можете
вводить команды и видеть результат, напечатанный в виде текста.

4.2 pwd

4.3ls

4.4ls-a

4.5rm

4.6history

4.7history

4.8command1;command2;command3;

4.9Обычно языки программирования, текстовые командные интерфейсы, языки
разметок текста (HTML, TeX, wiki-разметка) имеют дело со
структурированным текстом, в котором некоторые символы (и их комбинации)
используются в качестве управляющих, в том числе управляющих структурой
текста. В ситуации, когда необходимо использовать такой символ в
качестве «обычного символа языка», применяют экранирование.

R

4.10выводить подробный список, в котором будет отображаться владелец,
группа, дата создания, размер и другие параметры;

4.11набор символов, показывающий расположение файла или каталога в
файловой системе.

4.12 info

4.13crtl+alt+T
