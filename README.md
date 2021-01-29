# Prueba-Vass-NodeJs
Prueba de Node Js
Se adjunta codigo fuente de la prueba solicitada, cabe recalcar que mi conocimento es muy basico en Node JS, por lo cual pude hacer el endpoint de logueo ademas utilice ORM para la creacion de las tablas.
Para ejecutar el codigo:
1)en Visual studio code abrir el folder enviado(Tener instalado Mysql)
Se debe instalar mysql de manera local para que el orm cree la respectiva tabla de user e insertar un usuario 
2)Se debe compilar en proyecto usando el comando npm run dev 
para probar el login se debe ejcutar el siguiente  endpoint localhost:3000/login con  el metodo Post se debe enviar como body el usuario y contraseña 
{
usNombre:""
usPass:""
}
una vez validado el endpoint retornara un token el cual debe ser enviado en el header de la peticion que deseen acceder en este caso solo hay dos :
/users y users/{id} 
