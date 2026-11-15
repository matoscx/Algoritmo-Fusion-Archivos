# 📂 Algoritmo de Fusión de Archivos en C++

> *Implementación eficiente de un algoritmo de mezcla (merge) diseñado para combinar el contenido de dos archivos de texto ordenados en un tercer archivo de salida, manteniendo el orden ascendente mediante el uso de punteros a archivos y lógica de ordenamiento externo.*

Este proyecto demuestra el manejo avanzado de flujos de datos en C++, permitiendo procesar y ordenar secuencias numéricas directamente desde el almacenamiento secundario sin necesidad de cargar todos los registros simultáneamente en la memoria RAM.

---

## 💡 Características Técnicas

* **Manejo de Archivos:** Uso de funciones estándar de C como `fopen`, `fscanf`, `fprintf` y `fclose` para garantizar una correcta persistencia y lectura de datos.
* **Lógica de Mezcla Óptima:** Implementación de un ciclo condicional que procesa ambas entradas hasta que una se agota, seguido de un vaciado eficiente de los registros restantes.
* **Complejidad Lineal:** El algoritmo procesa cada registro una sola vez, garantizando un rendimiento fluido y rápido.

---

## 💻 Stack Tecnológico

* **Lenguaje:** C++
* **Compiladores Compatibles:** GCC, Clang o MSVC

---

## ⚙️ Uso y Ejecución

1. Asegúrate de tener un compilador de C++ instalado en tu sistema.
2. Coloca los archivos de texto (`entrada1.txt` y `entrada2.txt`) con los datos ordenados en la misma ruta del ejecutable.
3. Compila y ejecuta el programa para generar automáticamente el archivo de salida integrado.

---
*Desarrollado como práctica fundamental de estructuras de datos, persistencia y algoritmos de ordenamiento externo.* ✨
