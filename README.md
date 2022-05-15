# Deployment of the dockerized application on Heroku

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## Steps

1. heroku login

```shell
heroku login
```

2. heroku container:login

```shell
heroku container:login
```

3. heroku create luisguisadoapp

```shell
heroku create luisguisadoapp
```

4. heroku container:push web -a luisguisadoapp

```shell
heroku container:push web -a luisguisadoapp
```

5. heroku container:release web -a luisguisadoapp

```shell
heroku container:release web -a luisguisadoapp
```