Для того, чтобы данная программа начала работать необходимо:
1) установить базу данных postgres (sudo apt -y install postgresql)
2) установить драйвер psycopg2 для питона
3) войти в учетную запись postgres (по умолчанию) (sudo -i -u postgres)
4) создать роль (createuser --interactive) 
5) создать базу данных (createdb mephi)

Недоработки:
1) Меню (Все беды с меню можно разрулить в after_show_people())
2) Вывод на экран значений таблиц
