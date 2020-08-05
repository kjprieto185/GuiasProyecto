## Semana 3 - Crear los módulos, los servicios y la estructura de recursos

### Objetivos

---

Los objetivos de esta actividad son:

- Implementar la estructura de módulos y servicios en Angular.
- Implementar las pruebas unitarias de los servicios.

### Pasos previos

---

- Haber configurado el ambiente local.
- Tener el listado de las HU que se van a implementar `falta algo para identificar el recurso`.
- Realizar el tutorial ejemplo de este paso `falta completar este tutorial`.

### Descripción actividad

---

#### ![](./../../assets/images/individuo.png) Actividad individual

Cada integrante, para cada uno de los recursos involucrados en las historias de usuario asignadas, debe:

- Crear el módulo del recurso correspondiente siguiendo las convenciones de nombramiento.
- Crear las clases que representa el recurso: la básica y la detallada. Las clases necesarias en la representación detallada, de otros recursos, se definen en comentarios mientras los demás integran su código.
- Crear el servicio que accede el API REST para ese ese módulo.
- Programar el método `http get` para traer la colección de elementos del recurso.
- Programar la prueba del servicio.
- Verificar que todo esté funcionando.
- Realizar commit y solicitar un `pull request`.
- (`Aquí va un paso de aceptar o no el pull request debemos verificar con Gloria el proceso del flujo de trabajo para que quede igual al del otro curso`)

### Recursos

---

- [Tutorial crear módulo, servicio]()

### Entregables

---

- Repositorio de Github actualizado.

### Criterios de evaluación

---

- El código en el repositorio incluye al menos una prueba para cada servicio.

- Las pruebas de los servicios se ejecutan correctamente. Para esto el tutor descargará el proyecto del equipo y ejecutará el comando ng test. Se espera que todos los test pasen sin errores.
