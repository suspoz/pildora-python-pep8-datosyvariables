# pildora-python-pep8-datosyvariables
Intro a Python I: Tipos de datos y variables + pep8

# 🐍 Intro a Python I: Tipos de datos y variables

## 1. Descripción del proyecto

Esta píldora formativa es una introducción a Python para personas
que no tienen conocimientos previos de programación.

Aprenderemos a almacenar información mediante variables,
identificar los principales tipos de datos y realizar
conversiones entre ellos.

## 2. Objetivos de aprendizaje

Al finalizar la sesión serás capaz de:

- Declarar y asignar variables en Python.
- Diferenciar los tipos int, float, str y bool.
- Identificar el tipo de dato mediante type().
- Convertir datos utilizando casting.
- Aplicar convenciones básicas de escritura PEP 8.

## 3. Contenidos

1. ¿Qué es Python?
2. Variables y asignación dinámica.
3. Tipos de datos:
   - int: números enteros.
   - float: números decimales.
   - str: cadenas de texto.
   - bool: valores True y False.
4. Comprobación de tipos con type().
5. Conversión de tipos (casting).
6. Buenas prácticas: PEP 8.

## 4. Requisitos previos

- Python 3 instalado o acceso a Google Colab.
- Conocimientos básicos de informática.
- No es necesario tener experiencia programando.

## 5. Cómo ejecutar los ejercicios

1. Abre el notebook de Google Colab.
2. Ejecuta las celdas en orden.
3. Lee los comentarios y ejemplos.
4. Modifica los valores para comprobar los resultados.
5. Completa el reto práctico.

## 6. Ejemplos de código

### Variables

```python
nombre = "Ana"
edad = 25
altura = 1.65
es_estudiante = True
```

### Comprobar tipos

```python
print(type(nombre))
print(type(edad))
print(type(altura))
print(type(es_estudiante))
```

### Casting

```python
numero_texto = "123"
numero = int(numero_texto)

print(numero)
print(type(numero))
```

## 7. Reto práctico

Crea un pequeño programa que:

1. Declare una variable con tu nombre.
2. Guarde tu edad como número entero.
3. Guarde tu altura como decimal.
4. Cree una variable booleana llamada es_estudiante.
5. Muestre el tipo de cada variable utilizando type().
6. Convierta una cadena de texto numérica a entero.

## 8. Primeros auxilios (Troubleshooting)

### Error: NameError

**Causa:** Se utiliza una variable que no existe
o cuyo nombre está mal escrito.

**Solución:** Comprueba que la variable está declarada
y que escribes su nombre correctamente.

### Error: ValueError

**Causa:** Se intenta convertir un texto que no
representa un número válido.

**Ejemplo:**
```python
int("hola")
```

**Solución:** Comprueba que el texto contiene
un valor convertible.

### Error: TypeError

**Causa:** Se intenta realizar una operación
con tipos de datos incompatibles.

**Solución:** Comprueba los tipos con type()
y realiza una conversión si es necesario.

### Error: SyntaxError

**Causa:** Existe un error en la sintaxis del código,
como comillas o paréntesis sin cerrar.

**Solución:** Revisa la línea indicada por Python.

### Error: IndentationError

**Causa:** La indentación del código es incorrecta.

**Solución:** Mantén una indentación consistente,
utilizando normalmente 4 espacios.

## 9. Buenas prácticas (PEP 8)

- Utilizar nombres de variables descriptivos.
- Escribir variables en minúsculas.
- Separar palabras con guiones bajos (snake_case).
- Mantener el código ordenado y legible.

Ejemplo correcto:
```python
mi_variable = 10
nombre_usuario = "Ana"
```

## 10. Material de la píldora

- Presentación: Tipos de datos y variables.
- Notebook del formador: ejemplos resueltos.
- Notebook del alumnado: ejercicios con TODO.
- Reto práctico: aplicación de los conceptos.

## 11. Conclusión

Python es un lenguaje sencillo para empezar a programar.

Las variables permiten almacenar información,
los tipos de datos determinan qué información manejamos
y las conversiones nos permiten adaptar esos datos.

¡Sigue practicando y aprendiendo Python! 🐍
