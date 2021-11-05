# Hacking docker webapps:

DVWA:
-----
```bash
# mysql -h 127.0.0.1 -P 3336 -u root -pp@ssw0rd
docker run --rm -it -p 8081:80 sagikazarmark/dvwa //-p 3336:3306
```
------
BWAPP:
------
```bash
# Go /install.php
# Creds: bee:bug
docker run -p8081:80 santosomar/bwapp // -p 3336:3306
```

--------
WebGoat:
--------
```bash
# Go to /WebGoat/
# Creds: create new user
docker run -p 8081:8080 -t webgoat/webgoat-8.0
```

--------------------
OWASP Mutillidae II:
--------------------
```bash
# Click on: setup/reset the DB
docker run -p8081:80 santosomar/mutillidae_2
```
