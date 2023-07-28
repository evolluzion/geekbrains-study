# Работа с удаленным репорзиторием
* Создаем на [GitHub](https://github.com/) аккаунт.
* Создаем в нем репозиторий geekbrains-study и файл README.md

# Подключаем наш репозиторий через GIT
* Вводим команду для создания SSH ключа:
> ssh-keygen
* Получаем наш ключ в файле id_rsa.pub и смотрим его командой cat
* Копируем ключ и вставляем его на GitHub в Профиль - Settings - SSH & GPG Keys

# Копируем наш репозиторий в локальное хранилище
* Вводим команду **git clone** и указываем путь к нашему репозиторию *.git
* Переходим в папку с репозиторием через **cd** и работаем локально.

# Отправляем изменения через **git push**
* Отправили и закоммитили.

# Вносим изменения в файл на сайте GitHub
* Получаем изменения в локальный репозиторий через **git pull**

# Создали новую ветку и предлагаем изменения файла через **pull request**
* Делаем коммит и отправляем запрос на внесение изменений из новой ветки localbranch через git push -u origin localbranch