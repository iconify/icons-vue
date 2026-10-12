<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i-nsej1ln"/><path class="jte4c6-2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:porcupine-sharp" /></template>
<style>
.i-nsej1ln {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 17.5H3v-3.684l2.15-.516C6.9 11.5 9.5 10.75 12 10.75c4.25 0 7.5 2.75 7.5 6.75Zm3.75-6l2.5-7m1 6.25l3.5-7.25m-.25 7.9l4.5-5.9m-1.85 7.9l3.35-3.4M7 17.5v2m8.5-2v2");
}

.jte4c6-2i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 14.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
