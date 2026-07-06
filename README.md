# 🤖 Fundamentos de Robótica: Prácticas ABB IRB 120

Este repositorio contiene los proyectos desarrollados en **RobotStudio** para la asignatura de Fundamentos de Robótica, enfocados en el control del robot industrial **ABB IRB 120** mediante lenguaje **RAPID**.

---

## 📋 Descripción de las Prácticas

### 🎯 Práctica 1: Sistemas de Referencia (WorkObjects)
Implementación de un ciclo *Pick & Place* donde la pieza se coloca con precisión sobre una base utilizando un **WorkObject (Wobj)** personalizado. Esto permite al robot trabajar con coordenadas locales independientes del entorno.

### 🔀 Práctica 2: Selección de Destinos vía Controlador
Lógica de control donde el usuario, a través de la **FlexPendant (controlador virtual)**, interactúa con el programa para elegir entre 3 estaciones de trabajo diferentes, activando la subrutina correspondiente.

### 🏗️ Práctica 3: Automatización de Estructuras (Jenga)
Desarrollo de un algoritmo paramétrico para construir una torre. El robot solicita una altura (número de piezas) al usuario y calcula de forma autónoma la secuencia de apilamiento respetando las restricciones del sistema.

---

## 🛠️ Tecnologías y Herramientas
* **Software:** ABB RobotStudio
* **Robot:** ABB IRB 120
* **Lenguaje:** RAPID
* **Entorno:** Controlador Virtual (VC)

---

## 📂 Estructura del Proyecto

* [**Práctica 1: Sistemas de Referencia**](./Colocar_Mesa.rspag)
* [**Práctica 2: Selección de Destinos**](./Seleccion_Destinos.zip)
* [**Práctica 3: Torre tipo Jenga**](./Torres.rspag)
