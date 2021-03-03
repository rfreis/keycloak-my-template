# keycloak my template
This repository contains basic structure to run a Keycloak instance with custom template

## Prerequisites

If you have docker and docker-compose, you're ready to go.

* docker
* docker-compose

## Testing application

After clonning this repo, you should to run the containers.

```
docker-compose up
```

Application will be listening on port `8080`.
Check [localhost:8080/auth/admin/](http://localhost:8080/auth/admin/)

## References

[keycloak.org](https://www.keycloak.org/)
