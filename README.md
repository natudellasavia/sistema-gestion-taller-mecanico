TRABAJO PRÁCTICO FINAL DE LA MATERIA PROGRAMACIÓN II. UTN FACULTAD REGIONAL PACHECO.
1ER CUATRIMESTRE, AÑO 2025

TIPO DE PROYECTO: Sistema de gestión de archivos - Taller mecánico

El sistema a desarrollar permitirá gestionar las reparaciones que se llevan a cabo en un taller mecánico (que trabaja únicamente con algunas marcas en particular).
Contando con un menú principal y submenús que serán la interfaz gráfica para la gestión de los clientes, vehículos y las reparaciones propiamente.

Los vehículos serán registrados por tipo de vehículo (auto, camioneta, camión, micro omnibus), marca y patente como identificador único. El sistema permitirá listar la
información ordenándolos por marca y tipo de vehículo. Se podrá buscar la información de un vehículo en particular, como también filtrar por tipo de vehículo y cuáles se encuentran actualmente en taller.

Los clientes serán identificados por su cuit y además se registrará nombre, apellido, celular, email, dirección y clasificación de tipo de cliente (particular o empresa).
La información de los clientes podrá ser listada ordenada por cuil, apellido y tipo de cliente. Y filtrada por cuil y tipo de cliente.

Para poder cargar las reparaciones se tiene que haber cargado previamente la información del cliente y del vehículo.
Como cada cliente puede tener más de un vehículo o cada vehículo puede haber entrado al taller más de una vez, las reparaciones serán identificadas con un id único
y contarán además con el cuit del cliente, la patente del vehículo, descripción de la falla, importe, fechas de ingreso y de entrega (cuando corresponda).

Se podrán realizar listados ordenados según id reparación, cliente, vehículo e importe. 
Y se podrá filtrar la información con los mismos criterios, pudiendo hacerlo además por rango de importes y fechas de ingreso. 
Y saber cuáles son las reparaciones que se están llevando a cabo a la fecha actual
