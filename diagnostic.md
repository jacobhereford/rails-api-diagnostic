# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
To respond to the client)front end) requests and to hold all data in a database
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
model
```

Which layer in the MVC pattern communicates with the model?

```bash
the specific controller such as things controller to things model
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Because views are the things that the backend provide to the client to see
```

What does C.R.U.D stand for?

```bash
create read update delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
sql
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
HTTP GET POST DELETE PATCH UPDATE  SQL INSERT SELECT UPDATE DELETE
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
the request hits the controller which then sends it to the person controller and then
  to the person model which replies with the informations of person/1
```

What is the command to generate a new rails-api app?

```bash
rails-api new blog_app --skip-javascript --skip-sprockets --skip-turbolinks --skip-test-unit --database=postgresql
```

What is the command to start an instance of a rails server?

```bash
rails server
rails serve
rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
rake db:drop

rake db:create

rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails-api g scaffold pet name:string age:string
```

List two advantages of using serializers? (2 bullet points)

```bash
Allows you to have cleaner code
Saves you time


```
