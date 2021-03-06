Требования к проекту
====================
Введение
--------
Данный проект имеет название “Password Manager”. Он предназначен для пользователей, у которых есть множество регистраций на разных сайтах и, в свою очередь, логинов и паролей на них.

Продукт будет позволять удаленное хранение логинов и паролей пользователей в зашифрованном виде на сервере, к которым возможен доступ путем авторизации в данной программе.

Требования пользователя
-----------------------
### Программные интерфейсы

Проект потребует использования протокола TCP для передачи данных между сервером и пользователем для получения нужной информации с сервера.

Также проект будет использовать метод шифрации данных с ключом, которым будет являться слово, сгенерированное путем скрещения личных данных при создании аккаунта для данного приложения.

Кроме этого потребуется стороння библиотека Qt для создания удобной и функциональной GUI оболочки, с которой сможет легко обращаться любой пользователь.

### Интерфейс пользователя

При входе в программу приложение попросит Вас авторизоваться в системе, либо, как альтернативу, зарегистрироваться в системе. Далее, как только Вы вошли, у Вас появиться возможность просматривать сведения о ваших логинах и паролях на различных сайтах, а также дополнительную информацию о них информацию о них. Кроме этого, будет активна возможность добавления новых логинов и паролей к сайтам и удаление старой информации. Также по завершению работы программы будет происходить верификация данных локальных с данными сервера и, если были внесены некоторые поправки, то новый данные будут отправлены на сервер.

### Характеристики пользователей

Данное приложение будет простым и понятным для всех пользователей. Для его использования не нужно обладать высокой технической грамотностью и дополнительными знаниями, так как в приложение будет присутствовать удобная пошаговая графическая оболочка, которую без труда поймет любой человек.

### Предположения и зависимости

Повлиять на требование к системе может усовершенствование приложения в сфере безопасности. Например:
- переход на более безопасный протокол передачи данных
- добавление новых алгоритмов шифрования данных
- усовершенствование способа авторизации (переход на авторизацию по отпечатку пальца)

Кроме этого также может повлиять расширение функциональности программы и добавления новой функции такой как, автоматическая авторизация на сайтах, данные которых есть в базе авторизированного приложения Password Manager.

Системные требования
--------------------
### Функциональные требования

-	шифрование и дешифрование данных
-	передача на сервер и получение с сервера шифрованных данных 
-	добавление и удаление данных о сайтах, логинах и т.д.
-	авторизация в программе

### Нефункциональные требования

Для данного приложения на первом месте стоит требование к безопасности так как, люди будет хранить наиважнейшую информацию в виде логинов и паролей на различные сайты. Следовательно, если эти данные попадут в чужие руки, то могут нанести непоправимый вред пользователю.

И кроме этого, также важным является удобность и простота данного приложения с пользовательской точки зрения, в следствии того, что воспользоваться им могу люди разной технической грамотности. 
