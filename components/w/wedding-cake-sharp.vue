<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="diquzrbgv"/><path class="ej4_3wbll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wedding-cake-sharp" /></template>
<style>
.diquzrbgv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6.25h6v3H9zm-2.5 6h11v3h-11zm-2.5 6h16v3H4z");
}

.ej4_3wbll {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
