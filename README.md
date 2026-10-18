Módulo de priorización automática de tickets sobre GLPI 11.0.1 para Petrocasa.

# Módulo AIT ANS - Petrocasa, C.A.

Este repositorio documenta mi proyecto de pasantía profesional realizado en la Gerencia de Automatización, Informática y Telecomunicaciones (AIT) de Petrocasa. 

Nota: Por políticas de confidencialidad de la empresa, el código fuente y la base de datos no se encuentran públicos en este repositorio. Aquí se detalla la arquitectura, las tecnologías y los logros del proyecto.

## Descripción del Proyecto

La Gerencia AIT gestionaba todo el soporte técnico a través de correos electrónicos, lo que generaba pérdida de trazabilidad y falta de priorización. Para solucionarlo, desarrollé e implementé el módulo AIT ANS (Automated Ticket Intelligent Notification System), una extensión personalizada para GLPI 11.0.1.

## Tecnologías y Entorno

- **Servidor:** Linux Ubuntu 24.04 LTS
- **Stack:** LAMP (Linux, Apache, MySQL, PHP 8.2)
- **Aplicación Base:** GLPI 11.0.1
- **Desarrollo:** Scripts personalizados en PHP, consultas SQL y tareas programadas (Cron jobs).

## Logros y Funcionalidades Implementadas

- **Despliegue desde cero:** Instalación y configuración completa del entorno LAMP y GLPI en el servidor de la empresa.
- **Motor de Priorización Automática:** Desarrollo de scripts en PHP que evalúan la antigüedad de los tickets y ajustan su urgencia automáticamente mediante Cron jobs.
- **Base de Datos Personalizada:** Creación de la tabla `ait_ans_threshold` en MySQL para gestionar las reglas y umbrales de priorización.
- **Reportes de Auditoría:** Interfaz externa para visualizar logs de priorización y cambios en tiempo real.
- **Capacitación y Documentación:** Redacción de manuales técnicos y de usuario, además de entrenamiento al personal de la Gerencia AIT para el uso del sistema.
