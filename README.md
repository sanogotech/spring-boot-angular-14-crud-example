# Spring Boot + Angular 14 CRUD example

Full-stack Angular 14 + Spring Boot Tutorial CRUD Application in that:
- Each Tutorial has id, title, description, published status.
- We can create, retrieve, update, delete Tutorials.
- We can also find Tutorials by title.

![spring-boot-angular-14-example-crud.png](spring-boot-angular-14-example-crud.png)

> [Spring Boot + Angular 14 CRUD example](https://www.bezkoder.com/spring-boot-angular-14-crud/)

Run both Back-end & Front-end in one place:
> [Integrate Angular with Spring Boot Rest API](https://www.bezkoder.com/integrate-angular-spring-boot/)

More Practice:
> [Angular + Spring Boot: File upload example](https://www.bezkoder.com/angular-13-spring-boot-file-upload/)

> [Angular + Spring Boot: JWT Authentication and Authorization example](https://www.bezkoder.com/angular-13-spring-boot-jwt-auth/)

## Run Spring Boot application
```
mvn spring-boot:run
```
The Spring Boot Server will export API at port `8081`.

## Run Angular Client


```
* Désinstallation d'angular-cli
npm uninstall -g @angular/cli
```


```
npm cache clear --force
 * Installation d'angular-cli dernière version disponible
npm install -g @angular/cli
```

```
npm install
ng serve   (default port 4200)
or
* ng serve --port 8081
```
