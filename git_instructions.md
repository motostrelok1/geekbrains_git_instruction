* создаем локальную папку

* создаем файл

* заходим в vscode открывем созданную папку

* View -> Terminal в терминале пишем git init - инициализируем папку

* введем имя пользователя git config --global user.name "itisgood" 

* введем почту git config --global user.email "me@example.com"

* командой git status видим, что файл не отслеживается

* командой git add .\<имя файла> добавляем в репозиторий отслеживание файла

* заходим в файл и делаем изменения и обязательно сохраняемся Ctrl+S

* проверяем git Status, видим красным modified: <имя отслеживаемого файла>

* повторяем git add .\<имя файла> 

* пишем коммит git commit -m "<текст коммита>"

* проверяем командой git Status, получаем Your branch is up to date with 'origin/<имя репозитория> nothing to commit, working tree clean

* вводим команду git log и просматриваем изменения




