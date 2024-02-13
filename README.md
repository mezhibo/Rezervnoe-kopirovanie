Задание 1
Составьте команду rsync, которая позволяет создавать зеркальную копию домашней директории пользователя в директорию /tmp/backup
Необходимо исключить из синхронизации все директории, начинающиеся с точки (скрытые)
Необходимо сделать так, чтобы rsync подсчитывал хэш-суммы для всех файлов, даже если их время модификации и размер идентичны в источнике и приемнике.
На проверку направить скриншот с командой и результатом ее выполнения

Решение 1

![ALT TEXT](https://github.com/mezhibo/Rezervnoe-kopirovanie/blob/bdb63b4876da9912f6d424131ab4abcad3d1e139/IMG/1.jpg)

![ALT TEXT](https://github.com/mezhibo/Rezervnoe-kopirovanie/blob/f11c45c42a571cd3a180b01e765fe6aa1d17c342/IMG/3.jpg)


Задание 2
Написать скрипт и настроить задачу на регулярное резервное копирование домашней директории пользователя с помощью rsync и cron.
Резервная копия должна быть полностью зеркальной
Резервная копия должна создаваться раз в день, в системном логе должна появляться запись об успешном или неуспешном выполнении операции
Резервная копия размещается локально, в директории /tmp/backup
На проверку направить файл crontab и скриншот с результатом работы утилиты.


Решение 2 

![ALT TEXT](https://github.com/mezhibo/Rezervnoe-kopirovanie/blob/9883047f0e0e72503112838a52634dc34f0c2e8f/IMG/2.jpg)

![ALT TEXT](https://github.com/mezhibo/Rezervnoe-kopirovanie/blob/95dd9a2cfeeb3b34919512c7d6b493c11ca0403c/IMG/4.jpg)
