🎟️ Sistema Tunomático

📌 Descripción General

El presente proyecto consiste en el modelado arquitectónico completo de un Sistema de Gestión de Turnos Digitales (Tunomático), orientado a optimizar la administración de atención de clientes mediante un sistema automatizado de generación, visualización y control de turnos.

El sistema fue diseñado aplicando principios de diseño orientado a objetos y patrones de diseño UML, permitiendo representar tanto la lógica funcional como la arquitectura física del sistema.

🎯 Objetivos del Modelado

Representar funcionalmente el sistema mediante diagramas UML.
Aplicar patrones de diseño reconocidos.
Modelar la arquitectura física del sistema.
Simular una solución escalable y modular.
Documentar técnicamente el sistema de forma profesional.
👥 Diagrama de Casos de Uso UML

Casos de Uso

El diagrama de casos de uso representa la interacción entre los distintos actores del sistema y las funcionalidades principales del Tunomático.

Los actores identificados fueron Cliente, Recepcionista y Administrador, cada uno con distintos niveles de acceso y responsabilidad dentro del sistema.

Se utilizaron relaciones <> para representar funcionalidades obligatorias, como la generación automática de tickets y actualización de pantallas. Asimismo, las relaciones <> permiten modelar comportamientos opcionales, como la repetición de llamados o generación de reportes.

🧩 Diagrama de Clases UML

Diagrama de Clases

Patrón Singleton
El patrón Singleton fue aplicado en la clase GestorConfiguración con el objetivo de centralizar la configuración global del sistema, garantizando la existencia de una única instancia compartida entre todos los módulos.

Prototipo Patrón
El patrón Prototype fue utilizado en TipoTramite para permitir la clonación de configuraciones de atención sin necesidad de recrearlas manualmente.

Adaptador Patrón
El patrón Adapter fue implementado mediante AdaptadorSistemaExterno, permitiendo integrar sistemas legacy externos sin modificar la lógica interna del sistema principal.

🖥️ Diagrama de Implementación UML.

Implementación UML

La arquitectura física del sistema fue modelada utilizando una estructura cliente-servidor, separando claramente la interfaz de usuario, la lógica de negocio y los componentes externos.

El sistema considera nodos físicos como kioscos de atención, servidores de aplicación, base de datos, pantallas digitales e impresoras de tickets.

Las conexiones representadas mediante HTTP/REST, SQL y WebSocket permiten reflejar una arquitectura moderna y modular.

⚙️ Decisiones Arquitectónicas

La arquitectura del sistema fue diseñada bajo un enfoque modular y cliente-servidor, permitiendo desacoplar la lógica de negocio de los dispositivos físicos y componentes externos.

La utilización de patrones de diseño permitió mejorar la mantenibilidad, reutilización y escalabilidad del sistema, facilitando futuras integraciones con nuevas tecnologías y módulos de atención.

Asimismo, la separación de responsabilidades entre controladores, repositorios y componentes de visualización permitió estructurar el sistema de manera clara y alineada a buenas prácticas de ingeniería de software.

📖 Finales de Reflexiones

El desarrollo del modelado UML permitió comprender la importancia de una arquitectura bien estructurada y documentada antes de la implementación de software.

La utilización de patrones de diseño facilitó la modularidad, mantenibilidad y escalabilidad del sistema, permitiendo representar soluciones cercanas a entornos reales de desarrollo profesional.

📎 Nota

Este repositorio tiene un propósito exclusivamente académico y documental, enfocado en representar el modelado arquitectónico completo del sistema mediante diagramas UML y aplicación de patrones de diseño.