# Prolog Project

Project to studing distributed system book.

Commands:
```sh
# Init the project
go mod init github.com/tentativafc/prolog
# Install modules
go get github.com/gorilla/mux
# Call application
curl -X POST localhost:8080 -d '{"record":{"value": "123456"}}'
curl -X GET localhost:8080 -d '{"offset": 0}'
```