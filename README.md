# SIMPLE CRUD WITHOUT DATABASE
is a study to better understand the logic of the crud model using the golang language. the data is not persistent, that is, after the end of the service, it will be lost.

# Start service
to start the application use the command:

    go run main.go

# Build

If you want to build the tool, use the command:

    go build -o app main.go

So, you will create a binary for your operating system, this binary will be called "app", if you want you can change the name by editing the parameter after "-o".

# Dependencies
The project has only one dependency, I use gorilla mux as API handler, to install it to the project, use:

    go get tidy

# Rotas
the application has 5 basic routes, they are:

|Method |Route  | func 	
|---	|---	|---	|	
|GET   	|movies |get all movie
|GET   	|movies/{id}| get one movie
|POST   |movies | create movie
|PUT   	|movies/{id}| update movie
|DELETE |movies/{id}| delete movie
