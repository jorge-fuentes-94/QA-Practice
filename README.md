# 🧪 QA Automation Practice

Proyecto de automatización de pruebas que demuestra competencias en QA utilizando la API de Star Wars (SWAPI) para validar endpoints, datos y performance.


## 📋 Descripción

Este proyecto demuestra habilidades en Quality Assurance (QA) y automatización de pruebas mediante la implementación de un suite completo de tests para la API pública de Star Wars (SWAPI). El proyecto incluye pruebas funcionales, de integración, performance y validación de datos.

## 🎯 Objetivos del Proyecto

•
Demostrar competencias en QA y testing automatizado

•
Implementar diferentes tipos de pruebas (funcionales, integración, performance)

•
Validar APIs externas de manera sistemática y robusta

•
Aplicar mejores prácticas de testing y documentación

•
Crear reportes detallados de resultados de pruebas

##✨ Características

🔧 Tipos de Pruebas Implementadas

•
Pruebas Funcionales: Validación de endpoints y respuestas

•
Pruebas de Integración: Verificación de relaciones entre recursos

•
Pruebas de Performance: Medición de tiempos de respuesta

•
Pruebas de Validación de Datos: Verificación de esquemas y tipos

•
Pruebas de Casos Límite: Manejo de errores y casos edge

•
Pruebas de Regresión: Verificación de funcionalidad existente

## 🏗️ Características Técnicas

•
Framework de Testing: pytest con plugins especializados

•
Reporting: Reportes HTML detallados con métricas

•
Parametrización: Tests parametrizados para múltiples escenarios

•
Fixtures: Configuración reutilizable de datos de prueba

•
Mocking: Simulación de respuestas para tests unitarios

•
CI/CD Ready: Configuración para integración continua

## 🚀 Instalación y Configuración

Prerrequisitos

•
Python 3.8 o superior

•
pip (gestor de paquetes de Python)

•
Conexión a internet (para acceder a SWAPI)

Instalación Paso a Paso

1.
Clonar el repositorio

2.
Crear entorno virtual

3.
Instalar dependencias

4.
Verificar instalación

## 🧪 Ejecutar las Pruebas

Comandos Básicos

Bash


# Ejecutar todas las pruebas
pytest

# Ejecutar con reporte detallado
pytest -v

# Ejecutar con reporte HTML
pytest --html=reports/report.html --self-contained-html

# Ejecutar pruebas específicas
pytest tests/test_characters.py

# Ejecutar con cobertura
pytest --cov=src --cov-report=html


Opciones Avanzadas

Bash


# Ejecutar pruebas en paralelo
pytest -n 4

# Ejecutar solo pruebas marcadas
pytest -m "smoke"
pytest -m "performance"
pytest -m "integration"

# Ejecutar con diferentes niveles de verbosidad
pytest -v -s  # Mostrar prints
pytest --tb=short  # Traceback corto
pytest --tb=no  # Sin traceback

📊 Casos de Prueba Documentados

Test Cases por Endpoint

EndpointTest CasesCobertura/people/15 casos95%/planets/12 casos90%/starships/10 casos85%/vehicles/8 casos88%/films/6 casos92%/species/7 casos87%

Tipos de Validación

•
✅ Códigos de Estado HTTP: 200, 404, 500

•
✅ Esquemas de Respuesta: Campos requeridos y tipos

•
✅ Validación de Datos: Rangos, formatos, valores válidos

•
✅ Relaciones: Links entre recursos

•
✅ Performance: Tiempos de respuesta

•
✅ Casos Límite: IDs inválidos, requests malformados

## 🛠️ Tecnologías y Herramientas

TecnologíaVersiónPropósitoPython3.8+Lenguaje de programaciónpytest7.0+Framework de testingrequests2.28+Cliente HTTPpytest-html3.1+Reportes HTMLpytest-cov4.0+Cobertura de códigopytest-xdist2.5+Ejecución paralelajsonschema4.0+Validación de esquemas

## 🎯 Habilidades Demostradas

Competencias en QA

•
Diseño de Casos de Prueba: Creación sistemática de escenarios

•
Automatización: Implementación de suites de pruebas automatizadas

•
Validación de APIs: Verificación de endpoints REST

•
Testing de Performance: Medición y validación de rendimiento

•
Reporting: Generación de reportes detallados y métricas

Competencias Técnicas

•
Python Avanzado: Uso de frameworks y librerías especializadas

•
Testing Frameworks: Dominio de pytest y sus plugins

•
API Testing: Validación de servicios web REST

•
CI/CD: Integración con pipelines de desarrollo

•
Documentación: Creación de documentación técnica completa




