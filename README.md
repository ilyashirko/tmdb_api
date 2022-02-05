# tmdb_api
Упражнение на чтение кода. Фильмы с TMDB

# find_similar.py
Просит пользователя ввести путь к базе данных и ключевое слово для поиска фильма.  
Находит фильм который интересен пользователю.  
Генерирует рейтинг фильмов на основе сравнения каждого с выбранным фильмом.  
Выдает ТОП-8 фильмов похожих на выбранный фильм.  

# make_own_db.py
Запрашивает ключ доступа к базе фильмов TMDB.  
Если ключ актуален, скачивает базу фильмов с id от 0 до 999.  
Записывает скачанную базу в файл, выводит название файла на экран.  

# search_in_db.py
Открывает локальную базу фильмов.  
Просит пользователя ввести ключевое слово для поиска фильма.  
Выводит на экран фильмы, содержащие ключевое слово в названии.  

# tmdb_helpers.py
коллекция скриптов для работы с сайтом TMDB:
- отправка запросов на сервер
- загрузка базы фильмов на ПК
- проверка ключа доступа

# hello_api_TMDB.py [УДАЛЕНА КАК ОТЛАДОЧНАЯ] 
Загружает фильм №215 и выводит на экран его бюджет.  

# own_db_helpers.py [УДАЛЕНА КАК НЕ НУЖНАЯ]
Загружает локальную базу фильмов.  
Функция перенесена в search_in_db.py
