Una consultora de Recursos Humanos nos ha pedido que desarrollemos una solución
web para el proceso de alta de candidatos.

Han dividido la solicitud en dos pantallas, que deberán ser tratadas en 
archivos separados. Crear dichas pantallas. Todos los campos con "*" son de
compleción obligatoria.

1) forms-1-pantalla-1.html: "Datos Personales"

Nombre*

Apellido*

Teléfono*

E-mail*

Género* (Sólo se debe poder seleccionar una opción)

	-> Ágenero

	-> Género fluido

	-> Hombre cis

	-> Hombre trans

	-> Intersex

	-> Mujer cis

	-> Mujer trans

	-> Sin Género

	-> Otro

En caso de que sea seleccionada la opción "Otro", debe mostrar un nuevo campo
para completar el género manualmente. 

Fecha de Nacimiento* (formato dd/mm/aaaa)

Estado Civil* (Sólo se debe poder seleccionar una opción)

	-> Casadx

	-> Divorciadx

	-> Solterx

	-> Unidx Civilmente

	-> Viudx

2) forms-1-pantalla-2.html: "Información Laboral"

Rubro*

	-> Gastronómico

	-> Industria Farmacéutica

	-> Textil

	-> Automotriz

Años de experiencia *

Situación Laboral Actual*  (Sólo se debe poder seleccionar una opción)

	-> Relación de dependencia

	-> Desempleado

	-> Cuenta propia

	-> Trabajo informal

Cuenta con monotributo*  (Sólo se debe poder seleccionar una opción)

	-> Si

	-> No

Seleccione días y horarios en los que puede llamárselo para entervistas
telefónicas.
Nota: Debe haber un renglón con cada día de Lunes a Viernes, y al lado de cada
día 2 campos donde ingresar el horario (desde y hasta).

Por últmo, se pedirá al usuario que adjunte su CV en formato PDF. *

La url http://pic.giganetglobal.com/request-handler.php se deberá utilizar como
destino de los forms, de manera de poder testear que estén realizando de forma
correcta el envío de la información.

Pueden tomar como ejemplo o punto de partida a form-1-ejemplo-clase.html
que encontrarán en este mismo repo.

