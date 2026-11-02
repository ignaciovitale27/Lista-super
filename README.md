# Lista del Súper

App simple (un solo archivo, `index.html`) para armar la lista de compras revisando lo que hay en casa.

## Cómo se usa

1. **🏠 Revisar casa**: para cada producto tocá **✔ Hay** o **✘ No hay**.
   - Si tocás **Hay**, aparece **¿Cuánto hay?** para escribir la cantidad (ej: "2 paquetes", "medio kilo").
   - Si queda poco, marcá **"Queda poco, comprar igual"** y se suma a la lista.
   - Tocar de nuevo el mismo botón lo desmarca.
   - Abajo de todo se pueden **agregar** productos nuevos, y con la ✕ se borran.
   - **🎤 Con la voz**: tocá el micrófono verde y decí, por ejemplo, *"no hay rollo de cocina"*,
     *"hay dos paquetes de fideos"*, *"queda poco café"* o *"no hay leche ni azúcar"*. La app lo marca sola
     y muestra lo que entendió (con botón **Deshacer**). Si dice algo que no está en la lista, lo agrega.
     También se puede escribir la frase en el cuadro de texto.
2. **🛒 Comprar**: aparece sola la lista con todo lo que **no hay** (o queda poco). En el súper se van tildando. Se puede **mandar por WhatsApp** o copiar.
3. **📦 Lo que hay**: resumen de lo que hay en casa y cuánto.

Al terminar, **"Empezar revisión nueva"** borra las marcas pero deja los productos.

Todo se guarda solo en el celular (no necesita internet ni cuenta).

## Instalarla en el celular (como una app)

La app es instalable (PWA): queda con su ícono en la pantalla de inicio, se abre a pantalla completa
y funciona sin internet. No hace falta Play Store ni App Store.

1. Publicar la carpeta en un link `https://` (ver abajo).
2. Abrir ese link en el celular:
   - **Android (Chrome):** aparece el cartel **"Instalar"** arriba de todo (o menú ⋮ → *Instalar app*).
   - **iPhone (Safari):** botón **Compartir** ⬆️ → **"Agregar a inicio"**.
3. Listo: se abre desde el ícono 🛒 "Súper".

> El micrófono solo funciona desde un link `https://`, no abriendo el archivo directo.

### Dónde publicarla (gratis)

- **Netlify Drop** (lo más fácil): entrar a https://app.netlify.com/drop y arrastrar la carpeta con
  estos archivos. Te da un link al instante.
- **GitHub Pages**: Settings → Pages → elegir la rama. En repos privados requiere GitHub Pro;
  si el repo es público es gratis.
