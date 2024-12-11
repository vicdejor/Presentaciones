---
marp: true
title: introducción a los SSOO en Red
paginate: true
theme: uncover
header: Implantación de Sistemas Operativos
footer: Curso 2024-2025
style: |
  section {
    background-color: #ccc;
    text-align: center;
  }
  li{
    font-size: 42px;
  }
  h3{
    text-shadow: grey 1px 0 10px;
  }

---

## Introducción a los Sistemas Operativos en Red
![bg left](./assets/1.jpg)

---
### ¿Qué es un Sistema Operativo en Red?
![bg right fit](./assets/2.jpg)

---
* Un sistema operativo diseñado para gestionar recursos y servicios en una red.

* Permite que múltiples usuarios accedan a archivos, impresoras y otros recursos de forma compartida.

* Facilita la comunicación entre diferentes dispositivos en la red.

---
### Componentes clave

---
* El servidor:
    * ordenador, normalmente con prestaciones **elevadas**, que ejecuta servicios
* El cliente:
    * ordenador, normalmente con prestaciones **ajustadas**, que requiere los servicios de un equipo servidor
* El Middleware:
    * Es la parte del software del sistema que se encarga del **transporte** de los mensajes entre el cliente y el servidor

---
### El funcionamiento básico

---
![bg 90%](./assets/3.png)

---
### Arquitectura por niveles

---
1. Un nivel de presentación, que aglutina los elementos relativos al cliente
2. Un nivel de aplicación, compuesto por elementos relacionados con el servidor
3. Un nivel de comunicación, que está formado por los elementos que hacen posible la comunicación entre el cliente y el servidor
4. Un nivel de base de datos, formado por los elementos relacionados con el acceso a los datos

---
### Concepto de Sistema Operativo de Red

---
> Un Sistema Operativo de Red es una especialización del concepto genérico de sistema operativo que se centra en ofrecer un comportamiento de “**sistema único**” a una implementación cliente/servidor.

---
### Directrices a cumplir

---
<style>
.container{
    display: flex;
}
.col{
    flex: 1;
}
</style>

<div class="container">
    <div class="col">
        <ul>
            <li>Autenticación</li>
            <li>Confidencialidad</li>
            <li>Espacio de nombres</li>
            <li>Ubicación</li>
            <li>Administración</li>
        </ul>
    </div>
    <div class="col">
        <ul>
            <li>Protocolos</li>
            <li>Acceso a los recursos</li>
            <li>Replicación</li>
            <li>Tratamiento de los fallos</li>
            <li>Tiempo</li>
        </ul>
    </div>
</div>

---


