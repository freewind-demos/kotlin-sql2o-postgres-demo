Kotlin Sql2o with H2 Demo
=========================

Use [sql2o](https://github.com/aaberg/sql2o) to select/insert/update data from postgres.

Install postgres on your machine, and create a database by command:

```
createdb sql2o-demo -U freewind -w
```

Then run `Hello.kt` in you IDE.

Notice
------

You should use your role to create postgres db, and change it also in `Hello.kt` -> `USERNAME`.

Command to query roles:

```
psql -l
```