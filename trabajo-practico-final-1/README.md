# Sistema de Gestión de Biblioteca Digital

## Descripción

Sistema de consola en Python para gestionar libros, usuarios y préstamos de una biblioteca digital.

## Integrantes del grupo

- (Nombre y apellido)
- (Nombre y apellido)
- (Nombre y apellido)
- (Nombre y apellido)

## Conceptos implementados

- **Herencia**: `Usuario` hereda de `Persona`
- **Polimorfismo**: el método `mostrar()` se comporta distinto en cada clase
- **Composición**: `Prestamo` usa `Libro` y `Usuario` directamente
- **Agregación**: `Usuario` puede existir sin un préstamo
- **Decorador propio**: `@registrar_accion` muestra cada acción ejecutada
- **Metaclase**: `MiMeta` cuenta las instancias creadas de cada clase
- **Patrón de diseño**: no se usan clases externas, todo está en un solo archivo (simplicidad intencional)

## Cómo ejecutar

Requiere Python 3.10 o superior. No necesita instalar nada.

```bash
python main.py
```
