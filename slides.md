---
theme: ./theme
layout: cover
class: text-center
background: '/media/eu.jpg'
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: RR
---

# Rodrigo Rogovski

Quem é? Onde vive? Do que se alimenta?

<!-- <div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div> -->

<div class="abs-br m-6 flex gap-2">
  <!-- <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button> -->
  <a href="https://www.linkedin.com/in/rogovski/" target="_blank" alt="Linkedin"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-linkedin />
  </a>
  <a href="https://www.instagram.com/rfrogovski/" target="_blank" alt="Instagram"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-instagram />
  </a>
  <a href="https://github.com/rrogovski" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
  <a href="https://rogovski.dev/" target="_blank" alt="Blog"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <img src="/media/R.png" style="width: 25px">
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Quem é?

Um cara que escreve uns códigos aí, tenta tirar umas fotos como hobby, tenta arrumar tempo livre para jogar games, tenta ser o mínimo sedentário possível (dá trabalho 😆), mas na maior parte do tempo está estudando algo útil ou "inútil" mesmo.

- 📝 **Recém formado** - Acabei a faculdade de SI agora no primeiro semestre 2023. <small>Será que vai sobrar tempo para jogar agora?</small>
- 🌎 **Onde vive?** - No interior, de uma cidade do interior de MT, chamada Sinop
- 📷 **Fotógrafo?** - Ô tadinho. Mas a gente tenta
- 🧑‍💻 **Developer** - Sempre na versão beta

<br>
<br>

<!-- Read more about [Why Slidev?](https://sli.dev/guide/why) -->

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
layout: image-right
image: '/media/insta.png'
---

# Fotografia

<div>Geralmente publico algumas fotos no instagram</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# Fotografia

<div grid="~ cols-2 gap-4">
<div>

Inicialmente os planos de fotografia, eram de fotos do céu noturno. Mas como diria Joseph Climber, a vida é uma caixinha de surpresas. Não deu cmuito certo e comecei a fotografar aves com um grupo de observadores aqui da cidade. Essas fotos podem ser conferidas no site [WikiAves](https://www.wikiaves.com.br/perfil_rogovski)

</div>

<div>

<img border="rounded" src="/media/wikiaves.png">

</div>
</div>

<!--
Presenter note with **bold**, *italic*, and ~~striked~~ text.

Also, HTML elements are valid:
<div class="flex w-full">
  <span style="flex-grow: 1;">Left content</span>
  <span>Right content</span>
</div>
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
class: px-20
---

# Fotografia

<div>Primeiras tentativas de fotografia do céu noturno</div>

<div style="display: flex; justify-content: space-between;" grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" class="w-100" src="/media/astro01.jpg">

<img border="rounded" class="w-100" src="/media/astro02.jpg">

</div>

<div style="display: flex; justify-content: center;">

<img border="rounded" class="w-60 -m-t-25" src="/media/astro03.jpg">

</div>

<!-- Read more about [How to use a theme](https://sli.dev/themes/use.html) and
check out the [Awesome Themes Gallery](https://sli.dev/themes/gallery.html). -->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
class: px-20
---

# Fotografia

<div>Alguns momentos capturados por aí.</div>

<div grid="~ cols-2 gap-2" m="-t-2">

```yaml
---
POA - Guaíba
---
```

```yaml
---
Gavião Carijó
---
```

<img border="rounded" src="/media/pordosol.jpg">

<img border="rounded" src="/media/carijo.jpg">

</div>

<!-- Read more about [How to use a theme](https://sli.dev/themes/use.html) and
check out the [Awesome Themes Gallery](https://sli.dev/themes/gallery.html). -->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
class: px-20
---

# Fotografia

<div>Alguns momentos capturados por aí.</div>

<div grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" src="/media/poa01.jpg">

<img border="rounded" src="/media/gramado01.jpg">

</div>

<!-- Read more about [How to use a theme](https://sli.dev/themes/use.html) and
check out the [Awesome Themes Gallery](https://sli.dev/themes/gallery.html). -->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
class: px-20
---

# Fotografia

<div>Alguns momentos capturados por aí.</div>

<div style="display: flex; justify-content: space-between;" grid="~ cols-2 gap-2" m="-t-2">

<img border="rounded" class="w-80" src="/media/sinop01.jpg">

<img border="rounded" class="w-80" src="/media/sinop02.jpg">

</div>

<div style="display: flex; justify-content: center;">

<img border="rounded" class="w-80 -m-t-25" src="/media/sinop03.jpg">

</div>

<!-- Read more about [How to use a theme](https://sli.dev/themes/use.html) and
check out the [Awesome Themes Gallery](https://sli.dev/themes/gallery.html). -->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
preload: false
---

# Blog?

O Blog de um post só! 😱

<div class="w-10 relative mt-6">
  <div class="relative w-100 h-100">
  <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="/media/blog.png"
    />    
  </div>

  <div
    class="text-2xl absolute top-30 left-150 text-[#2B90B6]"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    <a href="https://rogovski.dev/" target="_blank" alt="Blog"
    class="text-xl opacity-50 !border-none !hover:text-white">
    rogovski.dev
  </a>
  </div>
</div>

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

<!-- [Learn More](https://sli.dev/guide/animations.html#motion) -->

</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
class: px-20
---

# Games

<div>Claro, embora esteja só na vontade 🤣</div>

<div style="display: flex; justify-content: center;">

<img border="rounded" class="w-100 m-t-15" src="/media/games01.jpg">

</div>

<!-- Read more about [How to use a theme](https://sli.dev/themes/use.html) and
check out the [Awesome Themes Gallery](https://sli.dev/themes/gallery.html). -->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
theme: ./theme
layout: cover
class: text-center
background: '/media/thatsall.jpg'
highlighter: shiki
lineNumbers: false
---