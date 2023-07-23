# DB setting
create table in the database that called "tutorials" with 4 column (id,title,description,published)
change permissions in app/config/db.config.js

## Project setup
```
npm install
```

### Run
```
node server.js
```


#### Commands to DB
post: localhost:8080/api/tutorials (and include in the body json with title, description, published)
get: localhost:8080/api/tutorials , localhost:8080/api/tutorials/{id}
