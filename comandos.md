Caracteres comodines :

- > Reemplaza dos o mas caracteres.
  > ? > Reemplaza a un caracter.

---

cd > Change Directory : Cambiar de directorios.
ll > List : Listar el contenido de la carpeta.
pwd > ... : Conocer la ruta absoluta donde estoy parad@.
clear / cls > Clear : Limpiar la pantalla.

---

touch [ Nombre del archivo ] > Crear un archivo.
mkdir [ nombre del archivo ] > Make Directory : Crear carpetas.
mkdir -p [ nombre de archivo ] > Make Directory : Crear carpetas con un sistema de archivos interno.

---

**OJO! CUIDADO! PELIGROSO!**

rm [ nombre del archivo ] > Remove : Eliminar archivos.
rm -rfd [ Destino ] > Remove -Recursivo + -Force + -Directorys : Eliminar carpetas y contenido.

---

cp [ archivo a copiar ] [ nuevo nombre ] > Copy : Copiar archivos.
mv [ archivo a mover ] [ destino / ] > Move : Mover un archivo a una carpeta.
mv [ archivo a renombrar ] [ nuevo nombre ] > Renombrar archivos.

---

cat [ Nombre del archivo ] > Ver el contenido de un documentos sin entrar en el mismo.
head [ Nombre del archivo ] > Ver las primeras lineas de un documento.
less [ Nombre del archivo ] > Ver el contenido de un documento con un pager.

echo '[ Contenido a imprimir ]' > Imprimir un texto en pantalla.

\***\* BUG \*\***

---

git init > Iniciar el programa de Git y transformar una carpeta en un repositorio.
git add [ nombre del archivo ] > Agregar archivos a Git de: fuera del flujo de trabajo a la **Staging Area**.
git add . > Agregan archivos a **todo** Git de: fuera del flujo de trabajo a la **Staging Area**.

git status > Conocer el estado de los arhivos dentro del repositorio.
git log > Muestra los commits del repositorio de manera breve.
git show > Muestra la informacion detallada relacionada con los commits.
git commit --amend > Reemplazar el commit anterior por un nuevo (OJO, cambia el HASH)

---

Texto que se agrega a un commit:

Estructura :
`[ Texto ]( [ Archivos ] ): [ Descripcion del commit, hasta 50 caracteres ].`
Ejemplo :
`DOCS (README.md): Creacion de documentacion.`

Lista de texto:

- Feat : Un nuevo complemento o funcion.
- Fix : Un problema o bug.
- Docs : Documentacion de una mejor comprension del programa.
- Style : Codigo de estilo.
- Refactor : Codigo refactorizado.
- Test : Codigo de prueba.
- `Perf` : codigo de mejoramiento de rendimiento.
