# LDB (Learn Development Bases)
En este repositorio podrás encontrar ejercicios para aprender los conceptos básicos del mundo del desarrollo.

---

# Trabajo en el Repositorio

## 📥 Cómo subir tus ejercicios

Para mantener una estructura organizada y evitar conflictos, te pedimos seguir el siguiente proceso:

1. **Crear una Rama:** Antes de empezar a trabajar en tus ejercicios, crea una rama con tu nombre de usuario o algún identificador único.
    - Ejemplo: `git checkout -b nombreDeUsuario-ejercicios`

2. **Trabaja en tu Rama:** Realiza todos los ejercicios propuestos y guarda tus cambios en esta rama. Puedes ver en que rama te encuentras con el comando `git branch`

3. **Commit y Push:** Una vez hayas finalizado, haz commit de tus cambios y súbelos a tu rama.
    - Ejemplo: 
      ```
      git add .  or  git add [nombre de los archhivos a subir]
      git commit -m "Ejercicios capítulo CLI completados"
      git push origin nombreDeUsuario-ejercicios
      ```

Recuerda mantener tu rama actualizada con la rama principal para tener siempre la última versión del material.

---

# Estructura de Directorios

Para mantener el repositorio organizado, te pedimos seguir la siguiente estructura de directorios al subir tus ejercicios:

- Un directorio principal con el nombre del capítulo (e.g., `Capitulo01-CLI`).
  - Dentro de este, un subdirectorio por cada ejercicio (e.g., `Ejercicio01`, `Ejercicio02`, ...).
    - Dentro de cada subdirectorio, coloca los archivos relacionados al ejercicio y un `readme.md` con cualquier explicación o comentario relevante.

Esto nos ayudará a mantener un orden y facilitará la revisión y el feedback.

---

# 📖 Capítulo 1: Introducción al CLI (Interfaz de Línea de Comandos)
En la era de las interfaces gráficas, llenas de colores, botones y animaciones, podría parecer que la interfaz de línea de comandos, o CLI (Command-Line Interface), es un remanente del pasado. Pero nada podría estar más lejos de la verdad. A pesar de su aparente simplicidad, el CLI sigue siendo una herramienta poderosa y esencial en el arsenal de cualquier desarrollador.

El CLI nos ofrece un acceso directo y sin restricciones a las entrañas de nuestro sistema, permitiéndonos ejecutar tareas complejas con una secuencia de comandos o incluso automatizar esas tareas. Al aprender a utilizar el CLI, no solo adquirirás una habilidad valiosa, sino que también ganarás una comprensión más profunda de cómo funcionan las computadoras y los sistemas operativos.

En este capítulo, nos adentraremos en el mundo del CLI, usando el shell `bash`, una de las interfaces de línea de comandos más populares y ampliamente utilizadas en el mundo Linux. Aunque puede parecer intimidante al principio, con práctica y paciencia, pronto te sentirás cómodo y confidente utilizando el `bash`.

## ✏️ Ejercicios:

### [Ejercicio 1](https://github.com/pentarix1996/learn_development_bases/tree/main/Chapter%201/Exercise%201)
### [Ejercicio 2](https://github.com/pentarix1996/learn_development_bases/tree/main/Chapter%201/Exercise%202)

## 📌 Apéndices:

### A. Requisitos previos:

1. **Conocimientos básicos de informática:** Se espera que los participantes tengan un conocimiento básico sobre cómo operar una computadora, abrir aplicaciones y navegar por la web.

2. **Sistema Operativo:** Los ejemplos y ejercicios en este capítulo se basarán en el shell bash de Linux. Si estás usando Windows o Mac, no te preocupes, te guiaremos en el proceso de configuración.
    - **Para usuarios de Windows:**  Te recomendamos instalar una máquina virtual con Ubuntu. Puedes seguir este [tutorial](https://personales.unican.es/corcuerp/Linux/Install_Ubuntu_On_Windows_10_Using_VirtualBox.html) para hacerlo paso a paso. Otra opción es utilizar el Subsistema de Windows para Linux (WSL). Sin embargo, para este curso, nos centraremos en la máquina virtual para asegurarnos de que todos los usuarios tengan una experiencia uniforme.

    - **Para usuarios de Mac:** Aunque macOS viene con su propio terminal y shell (que es similar a bash), te recomendamos seguir los mismos pasos que los usuarios de Windows para mantener la uniformidad en el aprendizaje. Sin embargo, si prefieres usar el terminal de Mac, la mayoría de los comandos deberían funcionar de manera similar.

### B. Recomendaciones adicionales:

1. **Práctica constante:** Como con cualquier habilidad nueva, la práctica hace al maestro. Te animamos a que practiques regularmente los comandos y ejercicios que te presentamos.

2. **Toma notas:** Aunque tendrás acceso a todos los materiales y comandos en este repositorio de Git, te recomendamos que tomes tus propias notas. Escribir a mano o teclear los comandos y sus funciones te ayudará a retener mejor la información.

---
