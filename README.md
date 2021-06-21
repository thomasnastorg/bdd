

Docker example with Apache, MySql 8.0, PhpMyAdmin and Php

- You can use MariaDB 10.1 if you checkout to the tag `mariadb-10.1` 
- You can use MySql 5.7 if you checkout to the tag `mysql5.7`

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open phpmyadmin MYSQL at [http://localhost:8000](http://localhost:8000)


Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !
