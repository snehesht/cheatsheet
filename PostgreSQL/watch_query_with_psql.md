PostgreSQL `psql` has `\watch [seconds]` command that executes the current query buffer every `n` seconds (defaults to 2s)

```sql
db=# select * from <table_name>;

db=# \watch 2
```

Documentation
[psql](https://www.postgresql.org/docs/current/app-psql.html)
