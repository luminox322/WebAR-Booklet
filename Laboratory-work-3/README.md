## Проста обробка текстових даних засобами оболонки Unix-подібних ОС інтерпретора команд ОС 

### Налаштування процесу документування рішень лабораторної роботи

2.1.1 Я виконав копіювання заздалегідь, саме тому немає цього скріну.

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.1.2.jpg)

Рис. 1 - Фрагмент екрану з рішення завдання 2.1.2 "Створити нову Git-гілку з назвою «Laboratory-work-3».
Перейти до роботи зі створеною гілкою."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.1.3.jpg)

Рис. 2 - Фрагмент екрану з рішення завдання 2.1.3 "Створити каталог з назвою «Laboratory-work-3». Перейти до каталогу."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.1.4.jpg)

Рис. 3 - Фрагмент екрану з рішення завдання 2.1.4 "В каталозі «Laboratory-work-3» створити порожній файл README.md,
використовуючи команду інтерпретатору командного рядку Bash."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.1.5.jpg)

Рис. 4 - Фрагмент екрану з рішення завдання 2.1.5 "Використовуючи текстові редактори, які пропонуються оболонкою Git Bash,
наприклад, текстовий редактор nano, додати до файлу README.md рядок тексту із темою
лабораторної роботи: «Проста обробка текстових даних засобами оболонки Unix-подібних
ОС інтерпретора команд ОС»."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.1.6.jpg)

Рис. 5 - Фрагмент екрану з рішення завдання 2.1.6 "Виконати операції з оновлення GitHub-репозиторію змінами Git-репозиторія
через послідовність Git-команд add, commit із коментарем «Changed by Local Git» та push." (Трапився якийсь баг командної строки, та ці рядки просто пропали, я повторив їх щоб показати, що немає що комітити та файл вже пушиться) 

### 1 Навігація по файловій системі через засоби оболонки Git Bash інтерпретатору командного рядку Bash

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.2.1.jpg)

Рис. 6 - Фрагмент екрану з рішення завдання 2.2.1 "Отримати перелік файлів поточного каталогу з урахуванням видимості
прихованих файлів."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.2.2.jpg)

Рис. 7 - Фрагмент екрану з рішення завдання 2.2.2 "Перейти до прихованого каталогу .git, використовуючи команду pushd з метою
швидкого повернення до попереднього каталогу у майбутньому."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.2.3.jpg)

Рис. 8 - Фрагмент екрану з рішення завдання 2.2.3 "Переглянути вміст файлу config, використовуючи редактор nano."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.2.4.jpg)

Рис. 9 - Фрагмент екрану з рішення завдання 2.2.4 "Отримати перелік файлів поточного каталогу з урахуванням наступних умов:
-  відображення списку файлів у псевдо табличному форматі;
-  впорядкування порядку слідування файлів за убуванням їх розміру."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.2.5.jpg)

Рис. 10 - Фрагмент екрану з рішення завдання 2.2.5 "Повернутися до каталогу, використовуючи команду швидкого повернення."

### 2 Налаштування псевдонімів команд оболонки Bash

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.3.1%262%263.jpg)

Рис. 11 - Фрагмент екрану з рішення завдання 2.3.1 та 2.3.2 та 2.3.3 "
-  Виконати команду зі створення псевдоніму виклику команди, пов’язаною з Bash командою у відповідності з таблицею 4. Перевірити роботу псевдоніму команди.
-  Виконати команду зі створення псевдоніму виклику команди, яка буде надавати поточну дату лише із поточним днем, місяцем та роком
-  Використовуючи текстовий редактор, розпочати редагування файлу .bash_profile та додати у файл два рядки зі створеними раніше псевдонімами виклику команд."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.3.5.jpg)

Рис. 12 - Фрагмент екрану з рішення завдання 2.3.5 "Повторно запустити GitBash-оболонку та перевірити роботу одного зі створених псевдонімів команд, щоб підтвердити їх автоматичну реєстрацію через файл .bash_profile"

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.3.6.jpg)

Рис. 13 - Фрагмент екрану з рішення завдання 2.3.6 "Скопіювати файл .bash_profile до каталогу «Laboratory-work-3» Git-репозиторію"

### 3 Робота з файлами через перенаправлення вхідних/вихідних потоків

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.1(1).jpg)
![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.1(2).jpg)

Рис. 14 та Рис. 15 - Фрагменти екрану з рішення завдання 2.4.1 "Створити файл з назвою як транслітерація вашого прізвища з прикінцевою цифрою 1, наприклад blazhko_1, використовуючи команду cat з перенаправленням stdin- потоку на stdout-потік так, що файл містив один рядок з вашими прізвищем та ім’ям."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.2(1).jpg)
![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.2(2).jpg)

Рис. 16 та Рис. 17 - Фрагменти екрану з рішення завдання 2.4.2 "Додати до створеного файлу через перенаправлення stdout-потоку ще один рядок з назвою вашої групи."

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.3(1).jpg)
![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.3(2).jpg)

Рис. 18 та Рис. 19 - Фрагменти екрану з рішення завдання 2.4.3 "Створити файл з назвою як транслітерація вашого імені з прикінцевою цифрою 2, наприклад blazhko_2, який містить два рядки, створені через перенаправлення stdout-потоку двох наступних команд:
- команда визначення назви поточного каталогу, в якому ви знаходитеся, формує перший рядок;
- команда визначення імені поточного користувача ОС, формує другий рядок;"

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.4(1).jpg)
![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.4(2).jpg)

Рис. 20 та Рис. 21 - Фрагменти екрану з рішення завдання 2.4.4 " Об`єднати два раніше створені файли в один файл командою cat зі створенням нового файлу, назва якого – транслітерація вашого прізвища та імені із суфіксом- розширенням .cat.txt;"

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.5(1).jpg)
![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.5(2).jpg)

Рис. 22 та Рис. 23 - Фрагменти екрану з рішення завдання 2.4.5 " Повторити об`єднання файлів, але вже командою paste зі створенням нового файлу, де назва файлу –транслітерація вашого прізвища та імені із суфіксом- розширенням .paste.txt"

![image](https://github.com/luminox322/WebAR-Booklet/blob/Laboratory-work-3/Laboratory-work-3/2.4.6.jpg)

Рис. 24 - Фрагмент екрану з рішення завдання 2.4.6 "В попередньому розділі та в цьому розділі було виконано завдання, які створювали файли у каталозі Git-репозиторію. Ці файли поки що мають статус неконтрольованих файлів, тому необхідно виконати Git-команди add та commit із коментарем «Changed by Local Git» для створення нового Git-знімку (нової Git-версії)."
