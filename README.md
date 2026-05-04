# Creación de una aplicación web de tres capas con Spring.NET y VB.NET

➡️ Curso relacionado:  
[Creación de una aplicación web de tres capas con Spring.NET y VB.NET](https://stahe.github.io/es-web3tier-dotnet-avril-2005/)

---

## Introducción

Este documento explica cómo desarrollar una **aplicación web de tres capas** utilizando **VB.NET**, **ASP.NET** y **Spring.NET**.  

El objetivo es mostrar cómo estructurar una aplicación separando claramente:
- la interfaz de usuario
- la lógica de negocio
- el acceso a los datos
El marco **Spring.NET** se utiliza para configurar y ensamblar los componentes de la aplicación utilizando el principio **IoC (Inversión de control)**.

Este enfoque permite, en particular, modificar la implementación de una capa sin afectar a otras partes de la aplicación. 

---

## Objetivos del tutorial

Los principales objetivos de este documento son:

- escribir una **aplicación web de tres capas**:
  - interfaz de usuario
  - capa de negocio
  - capa de acceso a datos
- configurar la aplicación con **Spring IoC**
- generar **varias versiones de la aplicación** cambiando la implementación de una o más capas para ilustrar la flexibilidad de la arquitectura. 

---

## Herramientas utilizadas

El tutorial se basa en las siguientes herramientas:

- **Visual Studio .NET** — entorno de desarrollo
- **Cassini** — servidor web para ejecutar la aplicación
- **NUnit** — marco de pruebas unitarias
- **Spring.NET** — configuración e integración de las distintas capas de la aplicación web

---

## Nivel del documento

Este documento está dirigido a un público de **nivel intermedio a avanzado**. Para comprenderlo es necesario dominar previamente varios conceptos relacionados con .NET y el desarrollo web. 

---

## Requisitos previos recomendados

Para seguir este tutorial de forma eficaz, se recomienda estar familiarizado con:

- el **lenguaje VB.NET**
- **el desarrollo web con ASP.NET**
- el principio de **IoC (inversión de control)**
- los fundamentos del marco **Spring.NET** 

---

## Recursos recomendados

Los siguientes recursos pueden resultar útiles para adquirir los requisitos previos:

- *Introducción a VB.NET a través de ejemplos*
- *Desarrollo web con ASP.NET 1.1*
- *Spring IoC para .NET*
- Documentación oficial de **Spring.NET**

---

## Contexto y enfoque didáctico

Este tutorial se inspira en un documento similar creado dentro del ecosistema Java:

**Arquitecturas de tres capas y arquitecturas MVC con Struts, Spring y Java**

El objetivo es demostrar que:

- **las arquitecturas Java (J2EE)** y **.NET** se basan en principios muy similares;
- las habilidades adquiridas en un entorno pueden **reutilizarse en el otro**. 

---

## Arquitectura presentada

La aplicación desarrollada sigue una arquitectura **MVC de tres capas**:

Serge Tahé, abril de 2005