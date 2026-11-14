<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n85zcbbbf"/><path class="p6udmsb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-denied" /></template>
<style>
.n85zcbbbf {
  d: path("M10.9 21.5H4.5v-19h15v7.1M8 7h8m-8 3.5h3.9");
}

.p6udmsb4d {
  d: path("M11.75 16.5a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0ZM15 15l3 3m0-3l-3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
