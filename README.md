# OTUS_Vagrant

Занятие 1. Vagrant-стенд для обновления ядра и создания образа системы

Выполнение: 
1) Запуск ВМ с помощью Vagrant.   
   Vagrant.file добавлен в репозиторий.   
   Создана ВМ с ОС Ubuntu 22.04, с 2-мя ядрами CPU и 1ГБ ОЗУ.   

    vagrant init bento/ubuntu-22.04 --box-version 202407.23.0   
    
   
3) Обновление ядра ОС.   
   Проверяем ядро до обновления:   
Linux vagrant 5.15.0-116-generic #126-Ubuntu SMP Mon Jul 1 10:14:24 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux   

   Обновляем:   
sudo apt update && sudo apt -y upgrade   

   Проверяем ядро после обновления:
   
5) Оформление отчета в README-файле в GitHub-репозитории. 
