# Reto github

Desde la siguiente __URL__ [https://api.github.com/users/](https://api.github.com/users/) obtendremos información de un usuario de __github__.

Por ejemplo para obtener información del usuario __webferrol__ es necesario escribir el enlace

Es necesario obtener información de los mismos mediante un __end point__ cuando consumimos la __API__

[https://api.github.com/users/webferrol](https://api.github.com/users/webferrol)

Los campos requeridos son:

1. Login
2. Nombre
3. Imagen del usuario

- [] Crear un nuevo proyecto en __Vite__ que podemos llamar __github-project__
- [] Crear un __mock__ donde poder mostrar la información sin tener que utilizar la __fetch API__.
  - Podemos mostrar la información en este punto por la consola del navegador
- [] Realizar el fetching de datos después de los puntos anteriores


Fichero __constants.js__

```js
const END_POINT_URL = 'https://api.github.com/users/'
const INITIAL_VALUE_GITHUB = {
  loading: false,
  avatar: '',
  login: '',
  errores: null
}

export {
  END_POINT_URL,
  INITIAL_VALUE_GITHUB
}
```