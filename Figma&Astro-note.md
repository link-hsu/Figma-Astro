## Figma
[Course Link](https://www.youtube.com/playlist?list=PL4cUxeGkcC9hZm9NYpd4G-jhoeEk0ls-- "Link here")
- [Figma hotkey](https://byxblife.com/figma_shortcuts/) 
- shift + a - 創建元件的auto layout 
- shift + i - open component bar
- Plugins
  - Lorem Ipsum
  - Feather Icons
  - Simpleicons

## Astro
[Course Link](https://www.youtube.com/playlist?list=PL4cUxeGkcC9hZm9NYpd4G-jhoeEk0ls-- "Link here")
- [Installation](https://docs.astro.build/en/install/auto/)
  - ```npm install astro```  
    ```npm install```  
    ```git init && git add -A && git commit -m "Initial commit" ```  
- [astro icon](https://www.npmjs.com/package/astro-icon)
  - ```npm install astro-icon```
  - ```// astro.config.mjs```  
    ~~~
    export default {
      vite: {
        ssr: {
          external: ["svgo"],
        },
      },
    };
    ~~~
  - ```// postcss.config.cjs```  

- [postcss](https://github.com/postcss/postcss)
  - ```npm i -D postcss autoprefixer```
- [Openprops](https://open-props.style/)
  - ```npm i -D open-props postcss-jit-props```