# Deno Oak JWT CRUD For You to Learn <3
## Minimum Blog Application 

### CRUD Operation

- [x] Sign-up Feature
- [x] Log-In Feature
- [x] Create Post Feature
- [x] Update Post Feature
- [x] Delete Post Feature
- [x] Get Post By ID Feature
- [x] Get All Post

### Experience to Learn

- [x] Learn How to Use Drun (Deno Runner)
- [x] Learn How to Make Router
- [x] Learn How to Protect Router
- [x] Learn How to Use JSON Web Authentication
- [x] Learn How to Hash using BCrypt
- [x] Learn How to Interact with PostgreSQL
- [x] Learn How to Handling Error
- [x] Learn How to Use Deno-nessie for Database Migration 

### Todo

- [ ] Schema Validation using Yup
- [ ] Testing
- [ ] Evaluate & Refactor

### Start the project 

First, cache all the modules, execute nessie and start the program :

```
deno cache ./deps.ts

deno run --allow-net --allow-read --allow-env https://deno.land/x/nessie/cli.ts migrate

deno run --allow-net --allow-env --allow-read src/index.ts
```

Dont forget to use drun or denon, my project use drun, install drun first :)