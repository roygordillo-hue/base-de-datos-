
## 📌 Ejercicios Demostrativos

---

### 🧩 Ejemplo 1 — Sistema de Biblioteca

> Una biblioteca registra libros y autores. Un libro puede tener varios autores y un autor varios libros. Los socios toman libros prestados; de cada préstamo interesan la fecha de retiro y la de devolución.

<img width="1024" height="637" alt="image" src="https://github.com/user-attachments/assets/90ebcaa4-f2a2-4437-9e63-6dd6bcee848e" />

---

### 🧩 Ejemplo 2 — Pedidos de Restaurante

> Los clientes realizan pedidos que contienen varios platos con distinta cantidad. Los platos se agrupan en categorías. Cada pedido lo atiende un único mesero. El precio del plato debe registrarse tal como estaba al momento del pedido, aunque luego cambie.

<img width="1024" height="403" alt="image" src="https://github.com/user-attachments/assets/4709fa58-1329-4c9c-9207-6094d51fa618" />

---

### 🧩 Ejemplo 3 — Clínica Médica

> Los pacientes solicitan citas; cada cita la atiende un médico a un paciente en fecha, hora y consultorio. De algunas citas se genera una receta que incluye medicamentos con dosis y duración. Cada médico pertenece a una especialidad.

<img width="1024" height="389" alt="image" src="https://github.com/user-attachments/assets/fbb1d60e-9abe-486b-b4df-f7f7764ef8d1" />


---

### 🧩 Ejemplo 4 — Sistema de Aerolínea

> Una aerolínea opera vuelos (cada uno con número, fecha, origen y destino), cada vuelo lo realiza un avión. Los pasajeros realizan reservas para un vuelo específico, indicando asiento y tarifa pagada en el momento de la reserva.

<img width="1024" height="267" alt="image" src="https://github.com/user-attachments/assets/97bb4431-2f3b-4ce0-b1e1-6ccc754ec0ba" />


---

## 📌 Ejercicios Propuestos

---

### 🧩 Ejercicio 5 — Empresa Discográfica

Una empresa discográfica necesita modelar los datos sobre sus diferentes recursos según las siguientes características:

* **Manager:** De cada mánager se almacena un identificador de manager y su nombre. Un manager representa a una serie de artistas.
* **Artista:** Un artista es representado por un manager. De los artistas se almacena su nombre completo (usando un único atributo) y su NIF.
* **Evento de promoción:** Los artistas participan en eventos de promoción para dar a conocer sus trabajos. En un evento de promoción pueden participar varios artistas. De un evento se almacena un identificador único, la fecha de celebración y el número de asistentes.

<img width="1024" height="170" alt="image" src="https://github.com/user-attachments/assets/641ca978-c0d8-4cc2-a43e-63ea472bf4c5" />

---

### 🧩 Ejercicio 6 — Tienda Informática

Se desea crear una aplicación para la gestión de una tienda informática. 

* La tienda dispone de una serie de productos que se venden a los clientes. De cada producto informático se desea guardar el código, descripción, precio y número de existencias. 
* De cada cliente se desea guardar el código, nombre, apellidos, dirección y número telefónico. Un cliente puede comprar varios productos en la tienda y un mismo producto puede ser comprado por varios clientes. 
* Cada vez que se compre un artículo quedará registrada la compra en la base de datos junto con la fecha en la que se compró el artículo. 
* La tienda tiene contactos con varios proveedores que son los que suministran los productos. Un mismo producto puede ser suministrado por varios proveedores. De cada proveedor se desea guardar el código, nombres, apellidos, dirección, provincia y número de teléfono.

<img width="1024" height="329" alt="image" src="https://github.com/user-attachments/assets/b0872eef-d63e-4b5c-ac1d-af918ffb535e" />


---

### 🧩 Ejercicio 7 — Discos Musicales

* La tienda vende discos de diferentes géneros musicales y cantantes.
* Cada género musical tiene un identificador.
* Cada disco tiene título, género musical, precio y cantante.
* De un cantante se registra el nombre y su país. Todo disco pertenece a un cantante y un cantante puede tener muchos discos. Además, un disco tiene un conjunto de canciones (identificador y título).
* Un disco tiene muchas canciones y una canción puede estar en varios discos. Interesa conocer la posición de una canción en un determinado disco.

<img width="1024" height="329" alt="image" src="https://github.com/user-attachments/assets/d4b19863-c050-46ae-a200-b9e0721e86d3" />


---

### 🧩 Ejercicio 8 — Camiones

Se desea informatizar la gestión de una empresa de transporte que reparte paquetes por toda España. 

* Los encargados de llevar los paquetes son los camioneros, de los que se quiere guardar la cédula, nombre, teléfono, dirección, salario y población en que vive. 
* De los paquetes transportados interesa conocer el código del paquete, descripción, destinatario y dirección del destinatario.
* Un camionero distribuye muchos paquetes, y un paquete sólo puede ser distribuido por un camionero. 
* De las provincias a las que llegan los paquetes interesa guardar el código de provincia y el nombre. Un paquete sólo puede llegar a una provincia. Sin embargo, a una provincia pueden llegar varios paquetes.
* De los camiones que llevan los camioneros, interesa conocer la matrícula, modelo, tipo y potencia. Un camionero puede conducir diferentes camiones en fechas diferentes, y un camión puede ser conducido por varios camioneros.

<img width="1024" height="381" alt="image" src="https://github.com/user-attachments/assets/0673a026-c129-4eda-8cc4-5b31c82a1801" />

---

### 🧩 Ejercicio 9 — Veterinaria

* Del **propietario** interesa: cédula, apellidos, nombres, dirección y teléfonos.
* De la **mascota** interesa: identificador, nombre, fecha de nacimiento y tipo. Un propietario puede llevar una o varias mascotas; una mascota la lleva uno y solo un propietario.
* Del **personal** de la clínica veterinaria interesa un código, la cédula y nombre. Entre el personal de la clínica se distingue a los **veterinarios** y los **auxiliares**, pudiendo haber otros tipos:
  * Del **veterinario** se guarda además su fecha de alta y especialidad.
  * De los **auxiliares** interesa su base de cotización.
* Las mascotas pasan consulta con los veterinarios. De manera que:
  * Un veterinario puede pasar consulta a ninguna o a varias mascotas.
  * Una misma mascota de la clínica ha pasado consulta una o más veces en fechas diferentes con varios veterinarios.
  * Al pasar consulta se realiza un diagnóstico.
* Cada propietario tiene un **familiar de contacto** para casos de emergencia. De este familiar interesa la cédula, nombre y teléfono. Si el propietario se da de alta en la clínica veterinaria, el familiar ya no interesa. El familiar es contacto de un solo propietario.

<img width="1178" height="457" alt="image" src="https://github.com/user-attachments/assets/bf80d57b-e376-445a-a3e2-1fcc6d591f46" />

## [Ir al inicio ](./README.md)

