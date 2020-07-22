# Actividad 4

Universidad Católica Andrés Bello
Facultad de ingeniería
Escuela de ingeniería informática
Desarrollo de software

##### Profesor:         
Carlos Barroeta   

##### Integrantes:
Gabriel Tovar
Miguel Coccaro
Christian Neira
 
## Plan de Pruebas

Historia de usuario: Como usuario quiero comprar puntos en la plataforma de petromiles
Entorno de pruebas: Selenium
Framework de pruebas: Mocha JS

### Escenario 1:

#### Pre-requisitos:

##### Requisitos para poder ejecutar la prueba:
Tener una cuenta de usuario registrada en Petromiles, en este caso se utilizará los datos del usuario perteneciente al correo miguele.coccaro@gmail.com.
Tener una cuenta bancaria registrada con la que pueda realizarse la compra de puntos. Nuevamente, el script de pruebas utilizará la información de la cuenta del correo antes mencionado.

#### Pasos que se realizarán en la prueba:

- Abrir la ruta  https://petromiles-frontend.herokuapp.com/.
- Ingresar los siguientes datos en el login, para acceder a la página web: 
- Email: miguele.coccaro@gmail.com
- Password: clave1234
- Desplegar el menú, dirigirse a la opción de compra de puntos (Add points).
- Escribir la cantidad de 4800 puntos a comprar.
- Elegir la cuenta bancaria 
- Presionar botón de comprar puntos (GET POINTS).
- Esperar al mensaje de agradecimiento por comprar puntos 
- Presionar ok.

#### Resultado esperado: 
Pueda comprar puntos sin ningún problema, luego esperar que se verifique la compra y obtener sus puntos en Petromiles. 
