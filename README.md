# 🏫 Sistema de Salón Inteligente (IoT & Gestión Académica)

> **Nota:** Este repositorio funciona como un caso de estudio técnico. El proyecto fue desarrollado como prototipo integral y el hardware/código fuente permanecen bajo resguardo institucional tras su presentación.

## 📋 Resumen del Proyecto
Desarrollo de un ecosistema de hardware y software para la automatización de un aula. El sistema permite el control eléctrico mediante microcontroladores, registro de asistencia automatizado con tecnología NFC y consulta de datos en tiempo real para padres de familia.

## 🛠️ Stack Tecnológico
* **Base de Datos:** PostgreSQL (Diseño relacional, gestión de registros y expedientes).
* **Backend & Escritorio:** C# (Lógica de negocio, interfaz administrativa, generación de reportes).
* **Hardware & IoT:** Arduino Uno, Módulos lectores NFC.
* **Frontend/Web:** Integración web para visualización remota.

## 🏗️ Arquitectura y Validación
1. **Módulo de Hardware:** Lector NFC conectado a Arduino para registrar entrada y habilitar el suministro eléctrico.
2. **Módulo Administrativo:** Aplicación de escritorio en C# que procesa datos del Arduino y ejecuta consultas en PostgreSQL para validar identidad.
3. **Validación (QA):** Ejecución de pruebas de funcionamiento continuo para asegurar la correcta comunicación entre los módulos físicos y el software de escritorio.
