# Database

[Oracle Database 11G Express Edition](https://www.oracle.com/database/technologies/xe-prior-release-downloads.html)

- **User**: `mybatis_practice`
- **Password**: `1234`

## Create User

```sql
CREATE USER MYBATIS_PRACTICE IDENTIFIED BY 1234;
```

## Grant Privileges

```sql
GRANT CONNECT, RESOURCE TO MYBATIS_PRACTICE;
```

> [!IMPORTANT]
> Enter and execute commands one by one.
