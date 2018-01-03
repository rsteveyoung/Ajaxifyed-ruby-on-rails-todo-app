# README

In order to run this app follow this brief guide:

### Dependencies
  - This example uses **PostgreSQL** which must be locally accesible to the application.

### Installation

#01 - Clone the repo and go to root dir:
```sh
$ git clone <git-url>
$ cd <app-root-dir>
```
#02 - Run bundle:
```sh
$ bundle install
```
#03 - In the root of the project create an **.env** file with this contents (replace corresponding params):
```sh
DB_DEV_NAME=MY_POSTGRES_DB_NAME
DB_USERNAME=MY_POSTGRES_USERNAME
DB_PASSWORD=MY_POSTGRES_PASSWORD
```
#04 - Run database commands:
```sh
$ rails db:create && rails db:migrate && rails db:seed
```
#05 - Start the app:
```sh
$ rails s
```

#06 - Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:3000
or
localhost:3000
```
License
----

MIT
