# Progressive Web App Example

Este template para la creación de proyectos basados en NextJS como Progressive Web App.

## Entorno

### Git

Asegurarse de tener instalado `git` . Esto se puede revisar muy facilmente a trevez del comando `git --version` . En caso de no estar instalado, se puede hacer a travez de los siguientes paso

- En linux, a travez del comando `sudo apt install git`.
- En Windows, a travez de la pagina oficial https://git-scm.com/

### NodeJS

Procurar tener actualizado `node.js` a la versión lts. Para saber si Node.js esta instalado en su sistema, abra una terminal y ejecute el siguiente comando `npm doctor`. El resultado debe ser la versión de `node ` y `npm`instalada. Si el comando no se encuentra o no se encuentran actualizados, se puede instalar `Node.js` mediante alguno de los siguientes pasos

- En windows, desde la [pagina oficial](https://nodejs.org/en/), descargando y ejecutando la versión `lts`.

- En Linux, a través de `nvm`.

  - Abrir una terminal y ejecutar alguno de los siguientes comando

    ```bash
    curl -o- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh) | bash
    ```

    ```bash
    wget -qO- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh) | bash
    ```

  - Cerrar la terminal y abrir otra para ejecutar el siguiente comando para verificar la correcta instalación`nvm --version` . Una vez observada la versión, ejecutar el siguiente comando para instalar Node.js

    ```bash
    nvm install --lts

## Instalación y ejecución

- 🛠Para instalar las dependencias ejecutar el comando `npm install`
- ⚒Para ejecutar el playground, usar el comando `npm run dev`
- ⚒Para construir el proyecto, usar el comando `npm run build`

Si desea, puede crear un ejemplo por su propia cuenta con los siguientes comandos

```bash
npx create-next-app --example progressive-web-app progressive-web-app
# or
yarn create next-app --example progressive-web-app progressive-web-app
# or
pnpm create next-app --example progressive-web-app progressive-web-app
```

## Características

- [TypeScript](https://www.typescriptlang.org/)
- [NextJS](https://nextjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [HeroIcons](https://heroicons.com/)
