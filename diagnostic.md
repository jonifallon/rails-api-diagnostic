# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
It takes user requests, routes them, processes them, and returns them to the user.
It stores all the models, dbs, methods, etc.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Model layer
```

Which layer in the MVC pattern communicates with the model?

```md
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
// your response here
```

What does C.R.U.D stand for?

```md
Create, read, update, destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
delete, show, update, destroy, create
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
-Browser parses url
-browser sends request to the server, usually with http request (get)
-server sends to the appropriate controller
-controller gathers data from models and returns to server
-server returns information back to the user's browser
```

What is the command to generate a new rails-api app?

```bash
rails new <application-name> --api
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
rake db:drop
rake db:create
rake db:migrate
db:test:prepare
rake db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
Pet > rails generate scaffold Post name:string age:integer

```
