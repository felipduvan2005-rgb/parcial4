# Introducción a Git y Markdown

## ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero que permite dar formato a texto usando una sintaxis sencilla. Es muy usado en documentación y archivos README.


# Git

## 1. ¿Qué es un repositorio en Git?
Un repositorio es una carpeta que contiene el historial completo de cambios de un proyecto. A diferencia de un proyecto normal, guarda versiones y permite colaboración.

## 2. Áreas principales de Git
- Working Directory: archivos actuales
- Staging Area: archivos preparados para commit
- Repository: historial guardado

## 3. Cómo representa Git los cambios
- Blob: contenido de archivos
- Tree: estructura de carpetas
- Commit: snapshot del proyecto
- Tag: referencia a commits

## 4. ¿Qué contiene un commit?
- Autor
- Fecha
- Mensaje
- Referencia al commit anterior

## 5. git pull vs git fetch
- fetch: descarga cambios sin fusionar
- pull: descarga y fusiona automáticamente

## 6. Branch
Una rama es un puntero a un commit. Permite trabajar en paralelo.

## 7. Merge
Fusiona ramas. Puede generar conflictos si se modificó la misma línea.

## 8. Staging (git add)
Prepara archivos para commit. Si se omite, no se guardan cambios.

## 9. .gitignore
Archivo que indica qué archivos no deben subirse (ej: .class, .env).

## 10. Commit amend
Permite modificar el último commit sin crear uno nuevo.

## 11. git stash
Guarda cambios temporales sin hacer commit.

## 12. Deshacer cambios
- git reset
- git revert
- git checkout

## 13. Remotos
origin: repo principal  
upstream: repo original en forks

## 14. Ver historial
- git log
- git diff
- git show


# Fundamentos de Programación en Java

## 15. Tipos primitivos en Java
- int
- double
- float
- char
- boolean
- byte
- short
- long

## 16. Estructuras de control
- if / else: decisiones
- switch: múltiples casos
- for: ciclos definidos
- while: ciclos condicionales

## 17. Nombres significativos
Mejoran la legibilidad y mantenimiento del código.

## 18. Programación Orientada a Objetos
Paradigma basado en objetos que combinan datos y comportamiento.

## 19. Pilares de la POO
- Encapsulación
- Herencia
- Polimorfismo
- Abstracción

## 20. Herencia en Java
Permite que una clase herede atributos y métodos de otra usando extends.

## 21. Modificadores de acceso
- public
- private
- protected
- default

## 22. Variables de entorno
Valores configurados en el sistema que usa Java (ej: JAVA_HOME).
