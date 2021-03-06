# Вступление
В ходе курса по алгоритмам вам придётся написать очень много кода на C++. Уже со второго-третьего контеста это будет единственный язык, на котором вы будете сдавать задачи. Этот урок поможет вам скачать среду разработки, проверить, что у вас всё работает, вы узнаете некоторые тонкости про cin и cout и научитесь использовать быстрый ввод-вывод.

# Где писать код?
### IDE
Скачайте [CLion](https://www.jetbrains.com/ru-ru/clion/), [VS Code](https://code.visualstudio.com/) или [Сodeblocks](http://www.codeblocks.org/downloads/26).  
CLion имеет бесплатный 30 дневный период, но за это время у вас появится студ. почта, через которую вы легко получите лицензию на все продукты JetBrains. При первом запуске вам предложат установить компилятор, следуйте инструкциям.  
Сodeblocks относительно других вариантов мало весит и быстро работает. Если у вас слабый компьютер, то рекомендуем его. Скачивайте с официального сайта версию, которая имеет название по типу codeblocks-20.03mingw-setup.exe. Так вы сразу установите и компилятор mingw.

Посмотрим на примере CLion как создать проект. Выберите в стартовом меню или через File опцию New Project. Можете изменить путь или версию C++. Проследите, чтобы она была хотя бы 11.  
В Codeblocks необходимо ещё выбрать console application в меню. Затем, как создастся проект, разверните в меню слева папку и найдите main.cpp, откройте его двойным нажатием.

### Текстовые редакторы с подсветкой синтаксиса
Другой вариант это редакторы с подсветкой. Например, [sublime text 3](https://www.sublimetext.com/3), [emacs](https://www.gnu.org/software/emacs/) или [vim](https://www.vim.org/download.php). В этом случае вам придётся самостоятельно ставить компилятор. На linux он уже стоит, на Mac вы можете найти простую инструкцию, как сделать это. На windows же установка может вызвать множество проблем, так что если вы пишете на плюсах первый раз - рекомендуем IDE.  
Компиляция происходит либо из командой строки, либо горячими клавишами. Например, в sublime это Ctrl+B.

# Задание
Скачайте и положите рядом файлы ```main.cpp``` и ```optimization.h```.  
Если вы выбрали текстовый редактор, то просто откройте ```main.cpp``` и приступайте.  
Если IDE, то замените ```main.cpp``` в проекте на скаченный и рядом киньте  ```optimization.h```. Приступайте к заданиям внутри ```main.cpp```.
