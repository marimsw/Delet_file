Удаление каталога
+ Проверка существования каталога: Если каталог не существует, выбрасывается FileNotFoundError.
+ Проверка, является ли это каталогом: Если указанный путь не является каталогом, выбрасывается NotADirectoryError.
+ Удаление каталога: Используется shutil.rmtree() для рекурсивного удаления каталога и его содержимого.
+ Обработка ошибок: Обрабатываются различные исключения:
+ FileNotFoundError: Если каталог не найден.
+ NotADirectoryError: Если указанный путь не является каталогом.
+ PermissionError: Если у пользователя нет прав на удаление каталога.
+ OSError: Для других ошибок, связанных с операциями ввода-вывода.
+ Exception: Для любых других непредвиденных ошибок.
# Delet_catalog
