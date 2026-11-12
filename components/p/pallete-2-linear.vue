<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGIHQypetX" class="n1mjunbsu"><path class="rl97opacl"/></mask><mask id="SVGjXBqqeYj" class="n1mjunbsu"><path class="ppk8bc7fq"/></mask><g class="h01tyzbfu"><path class="ev6lq472a"/><circle class="prtecqbfy"/><circle class="byr218scq"/><path mask="url(#SVGIHQypetX)" class="mchlg8k5w"/><path mask="url(#SVGjXBqqeYj)" class="naj_vpbeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pallete-2-linear" /></template>
<style>
.byr218scq {
  cx: 6.5px;
  cy: 11.5px;
  r: 0.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ev6lq472a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12.026c0 5.146 3.867 9.387 8.847 9.96c.735.085 1.447-.228 1.97-.753a1.68 1.68 0 0 0 0-2.372c-.523-.525-.95-1.307-.555-1.934c1.576-2.508 9.738 3.251 9.738-4.9C22 6.488 17.523 2 12 2S2 6.489 2 12.026Z");
}

.h01tyzbfu {
  fill: none;
  stroke: currentColor;
}

.mchlg8k5w {
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M11.085 7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0Z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.naj_vpbeh {
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M16 7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0Z");
}

.ppk8bc7fq {
  d: path("M16 7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.prtecqbfy {
  cx: 17.5px;
  cy: 11.5px;
  r: 0.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rl97opacl {
  d: path("M11.085 7a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
