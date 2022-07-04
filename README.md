### Пример структуры удаленной конфигурации МП

Для каждой версии МП отдельный файл. Поддерживаются значения типа boolean, int, string. Не
подразумевает конфигурации для отдельных пользователей. Подразумевается, что если искомый ключ не
найден для boolean поля, для него в МП подставляется false, т.к. удаленные фича-тоглы являются "
выключателями".

Для того, чтобы иметь ссылку на конфигурацию, достаточно подставить версию приложения:

https://raw.githubusercontent.com/mmarashan/remote-config-example/main/versions/3.14.json
https://raw.githubusercontent.com/mmarashan/remote-config-example/main/versions/3.15.json