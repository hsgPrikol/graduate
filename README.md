# graduate 2024

## Первым урок 
Первым делом вам надо настроить систему для работы.

## Установка WSL
Заходим в PowerShell и вводим следующую команду
```
wsl --install
```

Дальше необходимо войти в WSL и обновить систему новыми зависимостями.
```
sudo apt update
sudo apt upgrade
```

## Вам надо создать ssh ключ. Сделать это можно сделать следующей командой
```
sudo apt install ssh
```

## Генерация ключа ssh
```
ssh-keygen
```

## Установка git
```
sudo apt install git
git config --global user.name "username"
git config --global user.email "email@mail.ru"
```

## Основные команды для пользования
```
git clone <link> - склонировать репозиторий
git checkout -b <branchName> - создать новую ветку о текущей и перейти на неё
git add <filename> - добавить файл в остлеживание
git commit -m "your text" - зафиксировать изменения в коммите
git pull - получить изменения текущей ветки
git push - загрузить изменения в удаленный репозиторий 
```

## После необходимо установить утилиты для разработки
```
sudo apt install cmake build-essential gcc gdb
```



