# GORM Sqlite Driver

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

```go
import (
  "github.com/oSethoum/gorm/sqlite"
  "gorm.io/gorm"
)

// github.com/mattn/go-sqlite3
db, err := gorm.Open(sqlite.Open("file:gorm.sqlite?_fk=1&_pragma_key=secret&cache=shared"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.

### Pure go Sqlite Driver

checkout [https://github.com/glebarez/sqlite](https://github.com/glebarez/sqlite) for details

```go
import (
  "github.com/glebarez/sqlite"
  "gorm.io/gorm"
)

db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```
