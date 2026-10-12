<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w6vmmqbil"/><path class="yollplskt"/><path class="krrgt1wwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skunk-sharp" /></template>
<style>
.krrgt1wwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 14.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w6vmmqbil {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.25v-1.517l1.5-.583l3-1.15q3-1.125 6-.75c-.5-3.75 1.25-6.75 4-8c1.75-.75 3.75.25 3.75 2v1.5l-2 1c-1.75.75-2.5 2.5-2 4.5l.5 2l.925 3.467L16 19.5v.75h-2.25v-2.5H10v2.5H7.75V17H3z");
}

.yollplskt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 14.5c1.75-.6 3.75-.85 5.75-.6c.75-3.9 1.75-6.65 4-8.65");
}

</style>
