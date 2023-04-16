```
unzip data.zip -d data # this will unzip the data into the directory 'data'
psql -c "CREATE DATABASE \"Adventureworks\";"
psql -d Adventureworks < install.sql

```
To see the data
```
\c "Adventureworks"
\dt (humanresources|person|production|purchasing|sales).*
```
