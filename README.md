# Sistema de Inventario de Laboratorio

## 1. Descripción
Aplicación en Python para administrar y controlar los equipos tecnológicos del laboratorio.

## 2. Objetivo
Llevar un control estructurado de los equipos tecnológicos del laboratorio.

## 3. Usuarios
Personal de soporte técnico, administradores de laboratorio y docentes.

## 4. Funcionalidades
1. Registrar equipo
2. Listar equipos
3. Buscar equipo
4. Modificar estado
5. Eliminar equipo
0. Salir

## 5. Información de los equipos
Cada equipo contiene:
- `codigo`: Identificador único del equipo
- `nombre`: Nombre del equipo
- `tipo`: Categoría del equipo
- `estado`: Estado actual del equipo
- `ubicacion`: Lugar físico

## 6. Tecnologías
- **Lenguaje:** Python
- **Almacenamiento:** Archivos JSON (`data/equipos.json`)

## 7. Estructura del proyecto
inventario-laboratorio/
├── README.md
├── AGENTS.md
├── app.py
├── src/
│   └── inventario.py
└── data/
    └── equipos.json

## 8. Ejecución
python app.py