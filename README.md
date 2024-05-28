Zadanie 11

W celu uruchomienia kontenerów używamy polecenia
```
docker compose up -d
```
![image](https://github.com/patryczeko/lab11/assets/106553021/086a21d7-7f42-4360-945e-61eb5156396d)

Poleceniami docker network inspect możemy sprawdzić czy kontenery są poprawnie podłączone 
```
docker network inspect zadanie11_backend
docker network inspect zadanie11_frontend
```
![image](https://github.com/patryczeko/lab11/assets/106553021/5334b95e-867f-492c-bae1-93aa484d3267)

![image](https://github.com/patryczeko/lab11/assets/106553021/b10e6968-727e-4d7e-9660-fb34d1c85559)

Nginx jest dostępny na porcie 4001 a phpmyadmin na 6001
```
localhost:4001
localhost:6001
```

![image](https://github.com/patryczeko/lab11/assets/106553021/06d60af8-da53-48ad-bf44-7b5dbf208b83)

![image](https://github.com/patryczeko/lab11/assets/106553021/857024a3-8468-4da7-8527-d4f9846bdbe2)

![image](https://github.com/patryczeko/lab11/assets/106553021/305b22e4-59a9-4397-98e0-75b53d5ac8ac)

![image](https://github.com/patryczeko/lab11/assets/106553021/a185d03c-9d28-43e8-9416-7eb128a14cd5)

docker-compose inicjalizuje bazę testdb







