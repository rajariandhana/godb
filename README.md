materials from
https://go.dev/doc/tutorial/database-access

<code>mysql -u root -p</code> will open MySQL terminal.
```
create database recordings;
use recordings;
source ./create-recordings.sql
```

in normal terminal
```
go mod init example/godb
go get .
export DBUSER=root
export DBPASS=WhateverUveSetPass
```

run code by
```
go run .
```