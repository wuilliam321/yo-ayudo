# Yo Ayudo

La idea es tener una aplicación con la cual un **Donador**, pueda postear en la red un **producto o servicio**. Otro tipo de personas pueden **Solicitar** algún tipo de ayuda, y por su parte, un **Voluntario** pueda asistir a los diferentes lugares a buscar el mencionado producto o servicio.

## Objetivos

 * Brindar a las personas la opción de poder **Donar** productos y/o servicios sin moverse de su casa, para fomentar así quedarse en la misma y a su vez ayudar en un momento crítico.
 * Crear un registro de personas que requieren algún tipo de ayuda, sea **Ayuda Personal** o sea por **Ayudar a Otro**, este registro debe permitir recolectar la ubicación geográfica de la persona para poder detectar **Zonas de Importancia** para ayudar a tomar desiciones (crear comederos, merenderos, otros).
 * Poder organizar **Planes de Recogida** de aquellos productos y/o servicios donados y que estos que pueden ser utilizados según corresponda, de forma organizada para evitar que las personas se expongan innecesariamente.


## Casos de uso

### Solicitar Ayuda

#### **Soy una persona que necesito ayuda**
 > *Estoy en una situación compleja en la que no puedo salir, y necesito algún tipo de ayuda*
   1. Quiero poder indicar que necesito ayuda
   2. Quiero indicar mis datos personales (cédula, nombres, apellidos)
   3. Quiero indicar mis datos para poder ser contactado como dirección, ubicación, teléfono
   4. Quiero poder indicar la necesidad que tengo para facilitar la ayuda que necesito


#### **Soy una persona que quiero pedir ayuda para otro**
 > *Tengo un vecino que esta en una situación compleja y no tiene forma de comunicarlo, quiero poder ayudarle*
   1. Quiero poder indicar que necesito registrar una ayuda para otro
   2. Quiero indicar mis datos personales (cédula, nombres, apellidos)
   3. Quiero indicar mis datos para poder ser contactado como dirección, ubicación, teléfono
   4. Quiero poder indicar los datos de la **Persona a Ayudar**, de la misma forma en que registro mis datos personales
   5. Quiero poder indicar la necesidad que tiene la persona para facilitar la ayuda que necesito

### Ofrecer Ayuda/Donar (Voluntario/a)

#### **Soy una persona que quiere ser voluntario**
 > *Tengo plena disposición de ayudar a otros de la forma en la que sea posible, quiero que me contacten si es necesario*
   1. Quiero poder registrarme como voluntario
   2. Quiero indicar mis datos personales como cédula, nombres, apellidos.
   3. Quiero indicar mi ubicacion (dirección) y disponibilidad para que puedan luego buscarme (si resulta necesario).

#### **Soy un voluntario que quiero donar un servicio:**
 > *Tengo experiencia como cocinero/a y considero que puedo ayudar a estas personas en situaciones complejas*
   1. Quiero registrarme como voluntario.
   3. Quiero poder indicar el servicio que quiero ofrecer.
   4. Quiero registrar detalles del servicio como nombre y descripcion

#### **Soy un voluntario que quiero donar un producto:**
 > *Tengo algunos productos en casa que puedo donar y no debo salir de casa, quiero que vengan a buscarlo*
   1. Quiero registrarme como voluntario.
   2. Quiero registrar detalles del producto como nombre y descripcion incialmente, luego se podrá cargar imagenes entre otros
   3. Quiero indicar mi ubicacion (dirección) para facilitar la recogida del mismo (Si corresponde)

#### **Soy un voluntario que quiero ir y recolectar lo donado:**
 > *Tengo un medio de transporte que puedo poner a disposición para buscar donaciones o personas para llevarlos donde sea necesario*
   1. Quiero registrarme como voluntario.
   2. Quiero poder indicar que tengo medio de transporte seguro para buscar lo donado.
   3. Quiero indicar la disponibilidad que tengo para salir a buscar lo donado.
   4. Quiero indicar mi ubicacion (dirección) para facilitar la planificación de la ruta más adecuada
   5. Quiero ser notificado cuando una ruta esta disponible para ser recorrida

## Casos de Uso (Administrativos)

### Usuarios
#### Soy un administrador que quiere aprobar voluntarios
