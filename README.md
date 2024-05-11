<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Instalaciones requeridas

1. Docker
2. Nest CLI

```
npm i -g @nestjs/cli
```

# Ejecutar en desarrollo

1. Clonar repositorio
2. Instalar dependencias

```
npm install
```

3. Levantar la base de datos

```
docker compose up -d
```


4. Clonar el archivo __.env.template__ y renombrar la copia a __.env__
5. Levantar las variables de entorno definidas en el __.env__
6. Ejecutar la aplicación
```
yarn start:dev
```

7. Reconstruir la base de datos con la semilla
```
api/v1/seed
```

# Tecnologias usadas

- MongoDB
- NestJS
