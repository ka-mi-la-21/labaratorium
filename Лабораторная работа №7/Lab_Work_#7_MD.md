**РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**



Факультет физико-математических и естественных наук



Кафедра прикладной информатики и теории вероятностей



**ОТЧЕТ** **ПО ЛАБОРАТОРНОЙ РАБОТЕ № 7**



дисциплина: Операционные системы






Студент: Мухтарова Камила Айратовна.
Группа: НПИбд-02-20





**МОСКВА 2021 год **



**Цель работы:** ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.

**Ход работы:**

Для начала осуществила вход в систему, далее записала в файл file.txt названия файлов, которые содержатся в каталоге /etc, после этого дописала в этот же файл названия файлов, которые содержатся в домашнем каталоге. Вывела имена всех файлов, которые имеют расширение .conf, записала их в новый файл conf.txt

![img](https://lh3.googleusercontent.com/fNGb4auGu-OMIbXBlEx3nyPyCIiTRDV_vSV4hgMnYsLCh64zbt9hO7GCjTzI-mv1E-yqeZufViKItMVetDSvboW19TtuRv8IuHlZnDRLH9lKm7dgv7MggF1XzbmgBEVnZDV_0l3o)

(рис. 1) - запись и вывод содержимого файла


Вывела на экран файлы из домашнего каталога с названиями, которые начинаются на с, затем вывела на экран файлы из каталога /etc, которые начинаются с символа h



![img](https://lh6.googleusercontent.com/tazjnr5GG86qC63wlpT9O1I5Fyu9ZJ4lxf5rmd3wjEVAwsSUYSpqH1zQhAOgbvQ28h1hI1shafKF8S4oaUBPf05DBDIDGA5Krx_EVvIN9Y-syDBjHn-qCgpzhqD_EuoS6BsepkwL)

(рис. 2) - названия файлов по критериям

Также это можно выполнить другой командой: 

![img](https://lh6.googleusercontent.com/JzuYE0ZrEvvusZS2brOQcivtBJzorwixhLg9ww5Nwk5sv4-ZeUy8gzKqV74bDditirFApPK3_el136bgGgrdqzokHDcxIGbvqG6SeuPuDbdajLEvZGpfArTlVgXKKOYrd4Hv6nxq)

(рис. 3) - второй способ для названия файлов по критериям



Запустила в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log, затем удалила файл ~/logfile



![img](https://lh6.googleusercontent.com/u-lKddKAx41ipPesLoTEzOBzBjw8zrISkK2t5O_lP5rVmlTIH7ubwbLdQr8X7uWCcKtb0xTrQguxYmyUvAaqrpR2lk0FQEx0hc2tE3M4bGkliHLBL6Rx1mAgzawrZLpUbir16TTO)



 (рис. 4) - запуск процесса в фоновом режиме для записи

Запустила в фоновом режиме редактор gedit, определила идентификатор процесса двумя способами (2031), посмотрела опции команды kill с помощью man, завершила процесс gedit. 



![img](https://lh3.googleusercontent.com/6LbD6rI2uoFyaefbXzwtR_qEcNH1LoSmM8uNByBF9amfd1l5xDUqiEyHK591BQRHt4fe7P77fO6rjNoxzG-Mo5dEFww7eUq_eC2AYb4V_PbUbGEJXw9Okp8iJy9bWdcBbKSRNNB7)



(рис. 5) - запуск редактор gedit, команды, завершения процесса 


Опции команды kill: 



![img](https://lh3.googleusercontent.com/tsCfN5SRalQpJOlzlotVC0XzmUE7symBodjstExqMGod5bmjHG2FXRO9Ca55Q8M2MeiVPrZL4v0YiltffYOTJBIlzMk3SuLXtn1jwoELNREu1mwI0EU5cWiJSuFJV73NTsMGT1aN)

(рис. 6) - опции для kill

Посмотрела подробную информацию о командах df, du с помощью man

![img](https://lh6.googleusercontent.com/Pg1N4yFneiTjCOkFlZH8QG8BVdWBzhHILO4lBaV6D7ljZN3s_2VHoqjsGuXRRMkoZCzA_B0UFroqX7jjg2eQ8ZwWInshsMageHOBtKf2_LwIis5eMdi0wZLOGbapcm5vnJ-6I-Cv)

(рис. 7) - опции команды df



![img](https://lh4.googleusercontent.com/jvdnKtiGHmtvj5FCbtTlDdvJjbQ-MM1lW3YxIzOgJzzNrP8G4sTOHjdLCeRFXvKzxX1jeUJRDLpEGTEeYH8soheViroFdkRaTLvW-h-kOf9SjagMuDZLaSifZ8t6IoVWgKHjxifM)

(рис. 8) - опции команды df



Выполнила две команды: df, du

![img](https://lh6.googleusercontent.com/8KVCLh_PKnQTwHc3ryRlMrWU3lKZS0xK49V9Q1JuKAE3XgrKHu24LJ9E7N4GTVxkrb_J_00uiklnMS0zyg7iymq5emdgHFDi_29XQjb0t29TSy-5LBqntfSKh-LyhR0VJ-MPAHeJ)



(рис. 9) - исполнение команд df, du



Воспользовавшись справкой команды find, вывела имена всех директорий, имеющихся в домашнем каталоге.



![img](https://lh5.googleusercontent.com/eiJpVguzBRkc0puKuaVcz1nQOdiMmsJAJTo7cvwDClY3FRovGJI_5bYEr_MYMpqNJ-KZ_1yLF-f3ZLTTn7K9fOjftW9dP3wydpCB_fg1hVYyJiLK8YIx-QSNEAt_UhE9aH9p0PjT)



(рис. 10) - команда find с опциями

**Вывод:** ознакомилась с инструментами поиска файлов и фильтрации текстовых данных. Приобрела практические навыки по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.