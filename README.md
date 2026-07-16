# SR Executive — Página digital

Página profesional preparada para publicar el Executive Resume y añadir posteriormente Portfolio y LinkedIn.

## 1. Agregar el PDF

Copia tu Executive Resume dentro de la carpeta:

documents/

Renombra el archivo exactamente como:

executive-resume.pdf

La estructura debe quedar:

SR_Executive_Digital_Profile/
├── index.html
├── styles.css
├── assets/
│   └── sr-monogram.svg
└── documents/
    └── executive-resume.pdf

## 2. Abrir en Visual Studio Code

1. Abre Visual Studio Code.
2. Selecciona Archivo > Abrir carpeta.
3. Elige `SR_Executive_Digital_Profile`.
4. Abre `index.html`.
5. Ejecuta con Live Server.

## 3. Probar

- `Ver Executive Resume` debe abrir el PDF en otra pestaña.
- `Descargar PDF` debe descargarlo.
- Teléfono y correo deben funcionar como enlaces.

## 4. Publicación

Cuando esté revisada, podrá publicarse en GitHub Pages.
Después de publicar, la URL definitiva servirá para crear el código QR de la tarjeta de presentación.

## Importante

El QR se genera únicamente después de obtener la URL pública definitiva.
No conviene generar el QR antes, porque tendría que cambiarse si cambia la dirección web.

Actualizar Executive Resume

1. Abrir carpeta documents

2. Sustituir executive-resume.pdf

3. Guardar

4. git add .

5. git commit -m "Update Executive Resume"

6. git push

7. Esperar 1 minuto

Listo.