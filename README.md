# Vivaracha

Gimnasia para la cabeza, todos los días un poquito.

MVP de una app de entrenamiento cognitivo inspirada en Lumosity, pensada
para adultos mayores en Uruguay. Sin login, pensada para abrirse desde un
link de WhatsApp en una tablet o celular.

Incluye 4 ejercicios: Memoria, Atención, Reflejos y Razonamiento.

## Cómo publicarlo en GitHub Pages

Este repo ya tiene un primer commit con `index.html` listo. Los pasos que
quedan son los que solo vos podés hacer (requieren tu cuenta de GitHub):

1. Entrá a https://github.com/new y creá un repositorio nuevo.
   - Nombre sugerido: `vivaracha`
   - Dejalo **vacío** (sin README, sin .gitignore, sin licencia) — ya
     tenemos eso en este repo local.
   - Puede ser público o privado (GitHub Pages funciona en ambos casos
     si tenés un plan que lo permita; si es privado y tu plan es free,
     usá público).

2. GitHub te va a mostrar una URL del tipo:
   `https://github.com/TU_USUARIO/vivaracha.git`

3. Desde esta misma carpeta (la que descomprimiste), corré:

   ```bash
   git remote add origin https://github.com/TU_USUARIO/vivaracha.git
   git push -u origin main
   ```

   (Te va a pedir login — usá tu usuario y un Personal Access Token como
   contraseña, no la contraseña de tu cuenta. GitHub te lo explica si no
   tenés uno: Settings → Developer settings → Personal access tokens.)

4. En GitHub, entrá a **Settings → Pages** del repositorio.
   - En "Source", elegí la rama `main` y la carpeta `/ (root)`.
   - Guardá. En uno o dos minutos te va a dar una URL del tipo:
     `https://TU_USUARIO.github.io/vivaracha/`

5. Esa es la URL que le mandás a tu mamá por WhatsApp. Se abre directo en
   el navegador, sin instalar nada.

## Iterar

Cualquier cambio que quieras hacer: editás `index.html`, y corrés:

```bash
git add .
git commit -m "describí el cambio"
git push
```

GitHub Pages se actualiza solo, en general en menos de un minuto.
