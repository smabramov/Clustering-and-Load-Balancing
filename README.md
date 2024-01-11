# «Кластеризация и балансировка нагрузки» - Абрамов Сергей

___________________________________________________________________________

### Задание 1

1. Запустите два simple python сервера на своей виртуальной машине на разных портах
2. Установите и настройте HAProxy
3. Настройте балансировку Round-robin на 4 уровне.
4. На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.
 
 

Конфигурационный файл haproxy, находится в папке img фаил haproxy.cfg
`![tcp](https://github.com/smabramov/Clustering-and-Load-Balancing/blob/048610bc7e21c35738d2eb8db54f1c2d5ffb2e81/img/tcp.png)`
`![tcp1](https://github.com/smabramov/Clustering-and-Load-Balancing/blob/048610bc7e21c35738d2eb8db54f1c2d5ffb2e81/img/tcp1.png)`


---

### Задание 2


1. Запустите три simple python сервера на своей виртуальной машине на разных портах
2. Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
3. HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
4. На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.
 



Конфигурационный файл haproxy, находится в папке img фаил haproxy1.cfg

`![tcp2](https://github.com/smabramov/Clustering-and-Load-Balancing/blob/048610bc7e21c35738d2eb8db54f1c2d5ffb2e81/img/tcp%202.png)`

---