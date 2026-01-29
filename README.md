Made by Muhammad Suhaib Shaikh

create src/config/config.json
```
{
  "development": {
    "username": "root",
    "password": null,
    "database": "database_development",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
  "test": {
    "username": "root",
    "password": null,
    "database": "database_test",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
  "production": {
    "username": "root",
    "password": null,
    "database": "database_production",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

```
or go in source folder and execute the following command:
```
npx sequelize init
```
by executing the above command you get the migrations and seeders folder along witha a config.json in the src/config

- to run the server : nodemon src/index.js