# Repo para EIEC - DevOps - UNIR

Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas más.

## Cómo funciona

El programa `main.py` lee un fichero de texto con una lista de palabras (una por línea), las ordena alfabéticamente y muestra también la lista con elementos únicos.

Si el fichero no existe o no se indica correctamente, el programa utiliza una lista de palabras por defecto.

## Ejemplo de ejecución

Archivo `words.txt`:
banana
apple
apple
grape
cherry

Comando:
```bash
python3 main.py words.txt
```

Salida:
```bash
The words will be read from the file words.txt
['apple', 'apple', 'banana', 'cherry', 'grape']
Ahora se imprimira la lista con elementos unicos
{'apple', 'banana', 'cherry', 'grape'}
```

