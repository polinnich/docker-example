# docker-example

видео с демонстрацией - https://drive.google.com/file/d/14KJwt-j2L6yrjVhhUZ-qO7bHp49-r-WD/view?usp=sharing

файлы проекта: 
1) docker-compose.yml — файл для запуска контейнера
2) nginx.conf — конфигурация nginx 
3) site — index.html сайта

шаги работы
1) в powershell установлен wsl
2) скачан и установлен docker
3) создана папка проекта - D:\nginx-static и подпапка site
4) в подпапку site положила файл index.html с необходимым содержимым
5) в папку D:\nginx-static создала положила файлы conf и yml
6) в powershell выполнены следующие команды: cd D:\nginx-static, docker compose up -d
7) проверка работы сайта в браузере по адресу http://localhost:8080
8) проверка изменения текста в index html (замена "привет" на "hello", нажатие F5) без перезапуска контейнера - работает
