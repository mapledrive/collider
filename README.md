## Instructions to run
1. Navigate to folder */collider*
2. *NPM install*
3. *NPM run dev*
4. Navigate to localhost:8080



Инструкция по этапам разработки:
Переходим в корень диска c:  cd..  cd..
Клонируем config в папку fresh, например
https://github.com/mapledrive/config.git
Переходим в папку fresh :   cd fresh
Устанавливаем все пакеты npm install
Запускаем сервер для разработки npm run dev
В браузере заходим на адрес localhost:8080

В папке fresh/src/js открываем client.js и начинаем его изменять

При запуске установки пакетов из конфига npm ругается на устаревшие пакеты.
Можно установить пакет npm-check, который проверяет устаревшие зависимости пакетов.
npm install -g npm-check
Затем запустить интерактивное обновление в командной строке 
npm-check -u
Выбрать стрелками и пробелом и запустить на enter

Оригинальная версия config перегружается за 7 секунд на asus eee
Свежая обновленная версия config перегружается 6 секунд
Вывод: есть смысл обновить config и пользоваться более свежими пакетами

