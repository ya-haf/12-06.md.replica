## Задание 1
На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.

__Репликация master-slave__
Master — это основной сервер БД, куда поступают все данные. Все
изменения в данных (добавление, обновление, удаление) должны
происходить на этом сервере.
Slave — это вспомогательный сервер БД, который копирует все
данные с мастера. С этого сервера следует читать данные. Таких
серверов может быть несколько.

__Репликация Master-Master__
Master-Master репликации – это настройка обычной Master-Slave
репликации, только в обе стороны (каждый сервер является
мастером и слейвом одновременно).

## Задание 2
Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

<img src="https://github.com/ya-haf/12-06.md.replica/blob/main/img/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(284).png?raw=true" height=80% width=80%>
<img src="https://github.com/ya-haf/12-06.md.replica/blob/main/img/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(285).png?raw=true" height=80% width=80%>
<img src="https://github.com/ya-haf/12-06.md.replica/blob/main/img/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20(286).png?raw=true" height=80% width=80%>
